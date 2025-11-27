# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-27 at 21 32 25_5cf0d601](https://github.com/user-attachments/assets/5700ab83-349c-4604-90b7-d10db3384bb7)




## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
## Output:<img width="699" height="626" alt="image" src="https://github.com/user-attachments/assets/f675dccb-68cf-48ba-96b9-538393f5b790" />


## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is ------------

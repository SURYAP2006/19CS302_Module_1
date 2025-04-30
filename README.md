EX NO 1A : C PROGRAM TO INITIALIZE THE VALUE AS 5.8 & DISPLAY THE 
SAME. 
AIM: 
To write a program to initialize the value as 5.8 & display the same. 
 
ALGORITHM: 
1. Start 
2. Declare a variable value of type int 
3. Initialize value with value 5.8. 
4. Print the value of value using printf. 
5. End . 
 
 
PROGRAM: 
#include<stdio.h> 
int main() 
{ 
float a =5.800000; 
printf ("%.1f",a); 
return 0; 
 
} 
 
OUTPUT: 



![Screenshot 2025-04-30 134422](https://github.com/user-attachments/assets/9486c48c-a1de-4ff8-b230-93d71e48d4f0)


 
RESULT: 
Thus, the program is executed and verified successfully.











EX NO 1B : C PROGRAM TO CHECK WHETHER THE ATTENDANCE IS PRESENT 
USING SIMPLE IF STATEMENT). 
 
AIM: 
To write a program to check whether the attendance is PRESENT using simple if statement. 
 
ALGORITHM: 
1. Start. 
2. Declare a variable value of type char. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Check whether the attendance is PRESENT. 
6. If true, print "Present". 
7. If false, print " ". 
8. End. 
 
PROGRAM: 
#include<stdio.h> 
int main(){ 
char p1; 
scanf("%c", &p1); 
if(p1=='P') 
{ 
printf("Present"); 
} 
return 0; 
} 
OUTPUT: 
 


![Screenshot 2025-04-30 134814](https://github.com/user-attachments/assets/3898b71d-b465-45e2-96cb-ef3abba68551)

 
RESULT: 
Thus, the program is executed and verified successfully. 








EX NO 1C : C PROGRAM TO FIND NUMBER OF YEARS BASED ON 
PRINCIPLE,RATE & SIMPLE INTEREST. 
 
AIM: 
To write a C program to find number of years based on principle, rate & simple interest. 
  
ALGORITHM: 
1. Start. 
2. Declare the variables. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Calculate the number of years using the formula: 
6. End . 
 
PROGRAM: 
#include <stdio.h> 
#include <math.h> 
int main() 
{ 
float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r); 
si=((p*n*r)/100); 
ci=(p)*(pow((1+ r/100),n)); 
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci); 
return 0; 
} 
OUTPUT: 
 
 



![Screenshot 2025-04-30 135225](https://github.com/user-attachments/assets/7f19aa75-0dea-46a0-84e1-a68ccccf9f30)



RESULT: 
Thus, the program is executed and verified successfully.






EX NO 1D : C PROGRAM TO CHECK ElIGIBILITY FOR MARRIAGE (AGE >=21). 
 
AIM: 
To write a program to check eligibility for marriage using simple if statement. 
 
ALGORITHM: 
1. Start. 
2. Declare a variable value of type char. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Check eligible for marriage. 
6. If age >= 21, print "Eligible". 
7. If false, print " Not Eligible". 
8. End. 
 
PROGRAM: 
#include<stdio.h> 
int main(){ 
char p1; 
scanf("%c", &p1); 
if(p1=='P') 
{ 
printf("Present"); 
} 
return 0; 
} 
OUTPUT: 
 
 



![Screenshot 2025-04-30 135506](https://github.com/user-attachments/assets/ddef841a-3d0b-4b06-841f-100dea588ddc)


RESULT: 
Thus, the program is executed and verified successfully.

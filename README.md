
# EX 1 C program to initialize the value as 5.8 & display the same.
## DATE:
## AIM:
To write a program to initialize the value as 5.8 & display the same.

## Algorithm
1. Start 
2. Declare a variable value of type int 
3. Initialize value with value 5.8. 
4. Print the value of value using printf. 
5. End .  

## Program:
```
#include<stdio.h> 
int main() 
{ 
float a =5.800000; 
printf ("%.1f",a); 
return 0; 
 
} 
```

## Output:

![image](https://github.com/user-attachments/assets/5d7cae15-de01-4775-b062-3bc839f21cff)

# EX 2 C program to check whether the attendance is PRESENT using simple if statement.
## DATE:28\04\2025
## AIM:
To write a program to check whether the attendance is PRESENT using simple if statement.

## Algorithm
1. Start. 
2. Declare a variable value of type char. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Check whether the attendance is PRESENT. 
6. If true, print "Present". 
7. If false, print " ". 
8. End.  

## Program:
```
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
```

## Output:

![image](https://github.com/user-attachments/assets/c55b68e3-a4c1-4900-8b39-ad6bebe7a64b)

## Result:
Thus the program was executed and the output was verified successfully.

## Result:
Thus the program was executed and the output was verified successfully.


# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:28\04\2025
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm
1. Start. 
2. Declare the variables. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Calculate the number of years using the formula: 
6. End .    

## Program:
```
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
```

## Output:
![image](https://github.com/user-attachments/assets/fc4e3c25-2b86-451b-9ed7-a7b0692f4185)



## Result:
Thus the program was executed and the output was verified successfully.

# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:28\04\2025
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start. 
2. Declare a variable value of type char. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Check eligible for marriage. 
6. If age >= 21, print "Eligible". 
7. If false, print " Not Eligible". 
8. End.  

## Program:
```
#include <stdio.h>

int main() {
    int age;

    scanf("%d", &age);

    if (age >= 21) {
        printf("You are eligible for marriage.\n");
    } else {
        printf("You are not eligible for marriage.\n");
    }

    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/7a255bf5-6988-42b8-b339-996e6579924e)




## Result:
Thus the program was executed and the output was verified successfully.




# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1. Start. 
2. Declare three variable value of type int for marks. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Find total and average. 
6. Print the result 
7. End.    

## Program:
```
#include <stdio.h> 
int main() { 
    int sub1, sub2, sub3, total; 
    float average; 
    scanf("%d %d %d", &sub1,&sub2,&sub3); 
    total = sub1 + sub2 + sub3; 
    average = total / 3.0; 
    printf("\nTotal : %d\n", total); 
    printf("Average : %.2f\n", average); 
    return 0; 
} 
```

## Output:

![image](https://github.com/user-attachments/assets/ef557452-87c6-4a46-8235-b0ec5919d0d5)


## Result:
Thus the program was executed and the output was verified successfully.






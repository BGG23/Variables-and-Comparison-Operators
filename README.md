# Variable and Comparison Operators

## Task 1
### Assign a variable with each datatypes covered in the previous workshop The datatypes previous covered were “Boolean”, “String”, “Int”

- $BoolanVar = $True
- $StringVar = "This is a string"
- $IntVar = 42

![image](https://user-images.githubusercontent.com/91567318/160649557-9a13b142-85f7-476f-8f70-00bdc56c98be.png)

---

## Task 2
### List all variables currently loaded in to memory. The noun within the cmdlet is “Variable”

- Get-Variable

![image](https://user-images.githubusercontent.com/91567318/161072540-ffa45801-457b-4743-a929-541c488e0c30.png)

- Get-Variable BoolanVar

![image](https://user-images.githubusercontent.com/91567318/160652076-2afb029a-0a51-477b-a554-dfa8f31760a1.png)

- Get-Variable StringVar

![image](https://user-images.githubusercontent.com/91567318/160652316-421c13c7-816f-4b97-a3fa-ac3b1c36e227.png)

- Get-Variable IntVar

![image](https://user-images.githubusercontent.com/91567318/160652373-2d5c4eee-0f90-4e29-8a6f-c8e0d5d5351b.png)

---

## Task 3
### Multiple two Int variables together PowerShell can perform basic maths operators, such as “+”, “-“ and “*”

- $IntVar1 = 4
- $IntVar2 = 10
- $IntVar1 * $IntVar2

![image](https://user-images.githubusercontent.com/91567318/160652955-5d6d0eaf-95f3-452b-b7d9-2dde1907a28b.png)

---

## Task 4
### First declare two Int variables. Then divided the first variable by the second and assign the result to a variable named $VariableResult The easiest way to do this is within the Integrated Scripting Environment (ISE) using multiple lines of code

- $IntVar3 = 10
- $IntVar4 = 2
- $VariableResult = $IntVar3 / $IntVar4

![image](https://user-images.githubusercontent.com/91567318/160653300-57374bc1-46ea-461b-be31-074976f9e607.png)

![image](https://user-images.githubusercontent.com/91567318/161072318-0146ae27-078b-464c-9efc-0e7ced74c87e.png)


---

## Task 5
### Typecast a Variable as a “String” and assign it a value of 5 Remember to normal brackets [] rather than curly brackets {} when typecasting a variable

- [String]$TypecastVar = 5

![image](https://user-images.githubusercontent.com/91567318/160653517-6e0f045d-b7c5-429e-8b7b-329c1e7ab7de.png)

---

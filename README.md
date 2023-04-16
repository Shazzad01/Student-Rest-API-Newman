# Student-Rest-API-Newman


## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/13082503/2s93Xwz4Az

## Test case list:
1. ### Create Student
	> Create Data Sets Using the Dynamic Random Variables.

2. ### Verify Crated Student Details
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Middle Name
 	3. > Last Name
 	4. > Date of Birth

3. ### Update Student
	> In the test case you need to validate the following field values:
 	1. > Only Message
4. ### Verify Verify Updated Student Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Middle Name
	3. > Last Name
 	4. > Date of Birth

5. ### Create Technical skills Create Student Address
	> In the test case you need to validate the following field values:
	1. > Only Message

6. ### Create a Student Address
	> In the test case you need to validate the following field values:
	1. > Only Message

7. ### Get the Student's Full Details
	> In the test case you need to validate the following field values:
	1. > First Name
	2. > Middle Name
	3. > Last Name
	4. > Date of Birth
	5. > Language
	6. > Year Of Experience
	7. > Last Used Date
	8. > House Number
	9. > City
	10. > State
	11. > Country
	12. > Std Code
	13. > Home Address
	14. > Mobile

8. ### Delete Specific Student
	> In the test case you need to validate the following field values:
	1. > Only Message

## Newman Report Summary:
![Screenshot_1](https://user-images.githubusercontent.com/112342961/232345658-3cf64d74-3faa-4266-8b0e-e474780f5b44.png)

![Screenshot_2](https://user-images.githubusercontent.com/112342961/232345664-f61aaa29-56cb-48eb-954e-ec26af7528ae.png)

![Screenshot_3](https://user-images.githubusercontent.com/112342961/232345668-de2d9a76-2570-4ee2-b903-5ac3039f9ddc.png)

![Screenshot_9](https://user-images.githubusercontent.com/112342961/232345672-b4702f44-72ac-447c-ac23-cd5c7505bfbc.png)

![Screenshot_10](https://user-images.githubusercontent.com/112342961/232345678-0944092e-408c-4de2-b56e-16c360f7eb9f.png)

![Screenshot_11](https://user-images.githubusercontent.com/112342961/232345686-f77c01f2-640a-4ca5-b840-7ca6cc86ed5c.png)

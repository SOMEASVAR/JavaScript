# JavaScript
## 1. Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback: 'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18. 

Enter your age: 30

you are old enough to drive.

Enter your age:15

You are left with 3 years to drive
## Program:
```
var age=prompt("Enter your age:");
if(age>=18)
{
    console.log("You are old enough to drive.")
}
else
{
    age=18-age;
    console.log("You are left",age," with  years to drive")
}

```
## Output 1:
![image](https://user-images.githubusercontent.com/93434149/232670139-3abe081d-1ab6-4521-b776-433e301e3f5d.png)
## Output 2:
![image](https://user-images.githubusercontent.com/93434149/232684731-2a86cfdc-32c6-4656-8b83-e7bd2c0ddd23.png)


## 2. Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

Enter your age: 30

You are 5 years older than me
## Program:
```
var sai=prompt("Enter the age of sai:");
var som=prompt("Enter the age of som:");
var age;
if(sai>som)
{
    age=sai-som;
console.log("You are ",age," years older than me.")
}
else
{
    age=som-sai
    console.log("You are ",age," years younger than me.")
}
```
## Output 1:
![image](https://user-images.githubusercontent.com/93434149/232684925-544aeb96-cda8-4975-b6b7-011502f56862.png)


## 3. Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?

Enter a number: 2

2 is an even number

Enter a number: 9
## Program:
```
var number=prompt("Enter the number to check:");
if(number%2==0)
{
    console.log(number,"is an even number");
}
else
{
    console.log(number,"is an odd number");
}
```
## Output 1:
![image](https://user-images.githubusercontent.com/93434149/232685036-ced9a900-ce9e-47e4-8b4c-88808968bdd8.png)


## Output 2:
![image](https://user-images.githubusercontent.com/93434149/232685094-c2583105-e229-48c5-af21-d3f688599417.png)
 
 ## Github link:
 ```
 ```


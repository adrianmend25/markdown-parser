# Lab Report 2

## Code Change 1
![CodeDif1](CodeChange1.png)

[Failure-inducing input 1](test-file1.md)

Symptom :
![Symptom1](Symptom1.png)

Including a space within the URL should be invalid but this bug displays it as part of the link. 
In the case of the test file, [some thing . net] is returned which is invalid.

## Code Change 2
!![CodeDif2](CodeChange2.png)

[Failure-inducing input 2](test-file2.md)

Symptom :
![Symptom2](Symptom2.png)

While the file should just return an array of valid URL's, the 
links of the images are also returned when they are included in the file. 

## Code Change 3
!![CodeDif3](CodeChange3.png)

[Failure-inducing input 3](test-file3.md)

Symptom :
![Symptom3](Symptom3.png)

When additional parenthesis or brackets are included in the file, the program gets stuck in an infinite loop. 
It should instead ignore them and return the other valid URL's.

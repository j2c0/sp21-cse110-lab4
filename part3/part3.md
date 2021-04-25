1. The bug is that the two inputted numbers were not parsed into integers, so the sum of the two numbers was actually never computed since num1 and num2 are strings.
When adding num1 and num2, it is just concatentating the two strings & isn't adding the two values of the strings. This is why the program is not functioning as expected.
2. I would fix this by using the function parseInt to change the types of num1 and num2 into integers and not strings in the calculateSum method. The screenshot I included of my fix is on Visual Studio 
Code since it is much easier to read (I hope that's okay).
3. citylots.json
4. part2.js
5. 11.7 MB
6. 1.20s
7. 
8. 
9. 
10. 
11. 

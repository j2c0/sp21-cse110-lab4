1. The bug is that the two inputted numbers were not parsed into integers, so the sum of the two numbers was actually never computed since num1 and num2 are strings.
When adding num1 and num2, it is just concatentating the two strings & isn't adding the two values of the strings. This is why the program is not functioning as expected.
2. I would fix this by using the function parseInt to change the types of num1 and num2 into integers and not strings in the calculateSum method. The screenshot I included of my fix is on Visual Studio Code since it is much easier to read (I hope that's okay).
3. citylots.json
4. part2.js
5. 11.7 MB
6. 89 ms
7. User Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.85 Safari/537.36
8. Apache
9. Tue, 26 Jan 2021 22:14:13 GMT
10. application/json
11. fetchData @ part2.js:2 onclick @ (index):21


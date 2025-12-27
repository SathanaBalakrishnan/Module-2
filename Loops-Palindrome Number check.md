## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```
n=int(input())
t=n
r=0
while t>0:
    d=t%10
    r=r*10+d
    t//=10
if r==n:
    print("The given number",n,"is a Palindrome")
else:
    print("The given number",n,"is not a palindrome")
```
## Output

<img width="1087" height="177" alt="image" src="https://github.com/user-attachments/assets/8ce4acb3-c8bb-4734-829d-bd2b349f2e93" />

## Result
Thus, the program has been successfully executed .

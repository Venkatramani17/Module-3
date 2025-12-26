# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
~~~
      def remove(str):
          l=len(str)
      a=""
      n=int(input())
      for i in range(0,l):
          if i==n:
              a=a+""
          else:
              a=a+str[i]
      print(a)
~~~
## Output
<img width="641" height="237" alt="438840913-e6134872-fe3b-4946-ad27-15225b4ab9f1" src="https://github.com/user-attachments/assets/ed1bb9b3-60a6-48f7-8198-351e78cf30d2" />

## Result
Thus,the program has been executed successfully.


# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
~~~
list=[1,2,-8]
total=sum(list)
print(total)
~~~


## Output
<img width="272" height="115" alt="438833141-ae34950b-a538-42f3-bad0-a44b735d64c0" src="https://github.com/user-attachments/assets/28e95bf1-5f17-4fb3-8b27-35b2f9130599" />

## Result
Thus,the program has been executed successfully.
# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
~~~
      import re 
      l1=[]
      items=['goal', 'new', 'user', 'sit', 'eat', 'dinner'] 
      for i in items:
         if not re.search(r"e",i):
         l1.append(i)
      print(l1)
~~~
## Output
<img width="361" height="130" alt="438836768-626824d6-3660-470f-ac45-bcba6052fd64" src="https://github.com/user-attachments/assets/ca65a459-c353-40e3-a41e-a834408f4f9f" />

## Result
Thus,the program has been executed successfully.
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
# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
~~~
      string="google"
      if string==string[::-1]:
         print ("The entered string is palindrome") 
      else:
         print ("The entered string is not palindrome")
~~~


## Output
<img width="732" height="162" alt="438843771-1b15d3d8-a967-4d1e-8c50-d609a574eb1c" src="https://github.com/user-attachments/assets/d410264c-74b6-4717-8e71-d87819447122" />

## Result
Thus,the program has been executed successfully.
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
~~~


      tuplex = ("s", "8", "a", "v", "n", "g", "u", "r", "c", "e")
      print("n" in tuplex)
      print("8" in tuplex)
~~~
## Output
<img width="287" height="135" alt="438848455-39855931-dafa-4d80-afc7-8895211b4f24" src="https://github.com/user-attachments/assets/b979a119-932a-4920-ae2b-6082a7edea0d" />

## Result
Thus,the program has been execueted successfully.

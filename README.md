# Program to count the number of each vowels
# dictionary with each vowel a key and value 0
vowels = {"a":0,"e":0,"i":0,"o":0,"u":0}
a=input("enter the sentence ")
# small and capital letters problem
a = a.casefold()
# no. of vowels
for char in a:
   if char in vowels:
       vowels[char] += 1
print(vowels)

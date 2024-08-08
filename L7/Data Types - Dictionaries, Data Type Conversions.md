# Dictionaries


## 7.1.1. Introduction to Dictionary


```

✅ Dictionary is a Python data type to store multiple values.

◻ We use parenthesis () to define a dictionary.

◻ In dictionary we represent an element in the {key-value} format.

✅ Keys of the dictionary cannot be changed.

◻ dictionary() function is used to create an empty dictionary.

```

## 7.1.2. Understanding Dictionary


```python
mydict = {"game":"chess","dish":"chicken","place":"home"}
print(mydict.get("game"))
print(mydict['dish'])
print(mydict.get("place"))
mydict['game'] = "cricket" # change game chess to cricket using respective key
print(mydict['game'])
```

## 7.1.3. Accessing Elements of Dictionary


```python
# Taking input from the user for keys and values
key1 = input("key1: ")
value1 = input("value1: ")

key2 = input("key2: ")
value2 = input("value2: ")

key3 = input("key3: ")
value3 = input("value3: ")

# Construct the dictionary with the given key and value
dict={key1:value1,key2:value2,key3:value3}
print(dict)
# Print the values of dictionary using keys
print(value1)
print(value2)
print(value3)
```

# Data Type Conversions


## 7.2.1. Data Type Conversion - int,float


```python
a = int(input("Enter a value: "))
b = input("Enter b value: ")

# Convert "a" to floating point value.
print(float(a))
#Convert "b" to floating point value.
print(float(b))
```

## 7.2.2. Data Type Conversion - ord(), hex(), oct and complex()


```python
a = input("Enter character: ")
b = int(input("Enter an integer: "))

# Calculate and print the Unicode code point of 'a'
print(ord(a))
# Calculate and print the hexadecimal representation of 'b'
print(hex((b)))
# Calculate and print the octal representation of 'b'
print(oct(b))
# Calculate and print the complex number representation of 'b'
print(complex(b))
```




# 1. Palindrome Checker
# Problem: Check if a given string is a palindrome.
def is_palindrome(s):
    return s == s[::-1]

print(is_palindrome("racecar"))  # True
print(is_palindrome("hello"))    # False


# 2. Sum of List
# Problem: Find the sum of all elements in a list.
def sum_list(lst):
    return sum(lst)

print(sum_list([1, 2, 3, 4, 5]))  # 15


# 3. Fibonacci Sequence
# Problem: Write a function to return the nth Fibonacci number.
def fibonacci(n):
    if n <= 1:
        return n
    else:
        return fibonacci(n-1) + fibonacci(n-2)

print(fibonacci(5))  # 5


# 4. Factorial
# Problem: Find the factorial of a given number.
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n-1)

print(factorial(5))  # 120


# 5. Prime Number Check
# Problem: Check if a number is prime.
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n**0.5) + 1):
        if n % i == 0:
            return False
    return True

print(is_prime(7))  # True
print(is_prime(8))  # False


# 6. Reverse String
# Problem: Reverse a given string.
def reverse_string(s):
    return s[::-1]

print(reverse_string("hello"))  # "olleh"


# 7. Count Vowels
# Problem: Count the number of vowels in a string.
def count_vowels(s):
    vowels = 'aeiou'
    count = 0
    for char in s:
        if char.lower() in vowels:
            count += 1
    return count

print(count_vowels("hello"))  # 2


# 8. Find Largest Element
# Problem: Find the largest element in a list.
def largest_element(lst):
    return max(lst)

print(largest_element([1, 2, 3, 4, 5]))  # 5


# 9. List Odd Numbers
# Problem: Return a list of all odd numbers from 1 to n.
def odd_numbers(n):
    return [x for x in range(1, n+1) if x % 2 != 0]

print(odd_numbers(10))  # [1, 3, 5, 7, 9]


# 10. Remove Duplicates from List
# Problem: Remove duplicate elements from a list.
def remove_duplicates(lst):
    return list(set(lst))

print(remove_duplicates([1, 2, 2, 3, 4, 4]))  # [1, 2, 3, 4]


# 11. Count Occurrences
# Problem: Count the occurrences of an element in a list.
def count_occurrences(lst, x):
    return lst.count(x)

print(count_occurrences([1, 2, 2, 3, 2], 2))  # 3


# 12. Flatten Nested List
# Problem: Flatten a nested list into a single list.
def flatten(lst):
    result = []
    for item in lst:
        if isinstance(item, list):
            result.extend(flatten(item))
        else:
            result.append(item)
    return result

print(flatten([1, [2, [3, 4], 5], 6]))  # [1, 2, 3, 4, 5, 6]


# 13. Merge Two Lists
# Problem: Merge two lists into one.
def merge_lists(lst1, lst2):
    return lst1 + lst2

print(merge_lists([1, 2], [3, 4]))  # [1, 2, 3, 4]


# 14. List to Dictionary
# Problem: Convert a list of tuples into a dictionary.
def list_to_dict(lst):
    return dict(lst)

print(list_to_dict([('a', 1), ('b', 2)]))  # {'a': 1, 'b': 2}


# 15. Sum of Digits
# Problem: Find the sum of digits of a number.
def sum_of_digits(n):
    return sum(int(digit) for digit in str(n))

print(sum_of_digits(123))  # 6


# 16. Find Missing Number
# Problem: Find the missing number in a sequence from 1 to n.
def find_missing_number(lst, n):
    return sum(range(1, n+1)) - sum(lst)

print(find_missing_number([1, 2, 4, 5], 5))  # 3


# 17. Check Anagram
# Problem: Check if two strings are anagrams.
def is_anagram(str1, str2):
    return sorted(str1) == sorted(str2)

print(is_anagram("listen", "silent"))  # True
print(is_anagram("hello", "world"))    # False


# 18. Find Common Elements in Lists
# Problem: Find common elements between two lists.
def common_elements(lst1, lst2):
    return list(set(lst1) & set(lst2))

print(common_elements([1, 2, 3], [3, 4, 5]))  # [3]


# 19. Sum of Even Numbers
# Problem: Find the sum of all even numbers in a list.
def sum_even(lst):
    return sum(x for x in lst if x % 2 == 0)

print(sum_even([1, 2, 3, 4, 5]))  # 6


# 20. Find Duplicate Elements
# Problem: Find all duplicates in a list.
def find_duplicates(lst):
    return [item for item in set(lst) if lst.count(item) > 1]

print(find_duplicates([1, 2, 2, 3, 4, 4]))  # [2, 4]


# 21. Count Characters
# Problem: Count the number of characters in a string.
def count_characters(s):
    return len(s)

print(count_characters("hello"))  # 5


# 22. Remove Non-Alphabetic Characters
# Problem: Remove all non-alphabetic characters from a string.
def remove_non_alphabetic(s):
    return ''.join(filter(str.isalpha, s))

print(remove_non_alphabetic("abc123!"))  # "abc"


# 23. Check Armstrong Number
# Problem: Check if a number is an Armstrong number.
def is_armstrong(n):
    num_str = str(n)
    power = len(num_str)
    return sum(int(digit) ** power for digit in num_str) == n

print(is_armstrong(153))  # True


# 24. Calculate Area of Circle
# Problem: Calculate the area of a circle given its radius.
import math
def area_of_circle(radius):
    return math.pi * radius ** 2

print(area_of_circle(3))  # 28.274333882308138


# 25. Count the Words in a String
# Problem: Count the number of words in a string.
def word_count(s):
    return len(s.split())

print(word_count("Hello World"))  # 2


# 26. Generate Random Number
# Problem: Generate a random number between two numbers.
import random
def random_number(a, b):
    return random.randint(a, b)

print(random_number(1, 100))  # Random number between 1 and 100


# 27. Check Leap Year
# Problem: Check if a year is a leap year.
def is_leap_year(year):
    if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
        return True
    return False

print(is_leap_year(2020))  # True


# 28. Get ASCII Value of Character
# Problem: Get the ASCII value of a character.
def ascii_value(char):
    return ord(char)

print(ascii_value('A'))  # 65


# 29. Check Perfect Number
# Problem: Check if a number is a perfect number.
def is_perfect_number(n):
    divisors_sum = sum(i for i in range(1, n) if n % i == 0)
    return divisors_sum == n

print(is_perfect_number(6))  # True

# 30. Remove Punctuation from String
# Problem: Remove all punctuation from a string.
import string
def remove_punctuation(s):
    return s.translate(str.maketrans('', '', string.punctuation))

print(remove_punctuation("Hello, world!"))  # "Hello world"


# 31. Reverse Words in a Sentence
# Problem: Reverse the order of words in a sentence.
def reverse_words(s):
    return ' '.join(s.split()[::-1])

print(reverse_words("Hello world! How are you?"))  # "you? are How world! Hello"


# 32. Find the GCD (Greatest Common Divisor)
# Problem: Find the greatest common divisor of two numbers.
import math
def find_gcd(a, b):
    return math.gcd(a, b)

print(find_gcd(56, 98))  # 14


# 33. Merge Sorted Lists
# Problem: Merge two sorted lists into one sorted list.
def merge_sorted_lists(lst1, lst2):
    return sorted(lst1 + lst2)

print(merge_sorted_lists([1, 3, 5], [2, 4, 6]))  # [1, 2, 3, 4, 5, 6]

# 34. Check for Anagram of Two Strings (without sorting)
# Problem: Check if two strings are anagrams without sorting.
from collections import Counter
def is_anagram(str1, str2):
    return Counter(str1) == Counter(str2)

print(is_anagram("listen", "silent"))  # True
print(is_anagram("hello", "world"))    # False


# 35. Find the Longest Word in a Sentence
# Problem: Find the longest word in a sentence.
def longest_word(s):
    words = s.split()
    return max(words, key=len)

print(longest_word("Find the longest word in this sentence."))  # "sentence."


# 36. Check if String is a Number
# Problem: Check if a string is a valid number.
def is_number(s):
    try:
        float(s)
        return True
    except ValueError:
        return False

print(is_number("123.45"))  # True
print(is_number("hello"))   # False


# 37. Remove All Occurrences of a Character from String
# Problem: Remove all occurrences of a character from a string.
def remove_char(s, char):
    return s.replace(char, '')

print(remove_char("hello world", "o"))  # "hell wrld"


# 38. Check if a List is Sorted
# Problem: Check if a list is sorted in ascending order.
def is_sorted(lst):
    return lst == sorted(lst)

print(is_sorted([1, 2, 3, 4]))  # True
print(is_sorted([1, 3, 2, 4]))  # False


# 39. Count Words in a Sentence
# Problem: Count the number of words in a sentence.
def count_words(s):
    return len(s.split())

print(count_words("This is a test sentence."))  # 5


# 40. Find the Second Largest Element in a List
# Problem: Find the second largest element in a list.
def second_largest(lst):
    unique_lst = list(set(lst))
    unique_lst.sort()
    return unique_lst[-2] if len(unique_lst) > 1 else None

print(second_largest([1, 2, 3, 4, 5]))  # 4


# 41. Check if Number is Even or Odd
# Problem: Check if a number is even or odd.
def is_even_or_odd(n):
    return "Even" if n % 2 == 0 else "Odd"

print(is_even_or_odd(7))  # "Odd"
print(is_even_or_odd(8))  # "Even"


# 42. Sum of Numbers in a String
# Problem: Find the sum of all numbers in a string.
import re
def sum_of_numbers_in_string(s):
    numbers = re.findall(r'\d+', s)
    return sum(int(num) for num in numbers)

print(sum_of_numbers_in_string("abc123 def45 ghi67"))  # 235


# 43. Remove All Whitespaces from String
# Problem: Remove all whitespace characters from a string.
def remove_whitespaces(s):
    return s.replace(" ", "")

print(remove_whitespaces("Hello World!"))  # "HelloWorld!"


# 44. Convert Celsius to Fahrenheit
# Problem: Convert Celsius to Fahrenheit.
def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32

print(celsius_to_fahrenheit(0))  # 32.0


# 45. Find the Sum of Even and Odd Numbers
# Problem: Find the sum of even and odd numbers in a list separately.
def sum_even_odd(lst):
    even_sum = sum(x for x in lst if x % 2 == 0)
    odd_sum = sum(x for x in lst if x % 2 != 0)
    return even_sum, odd_sum

print(sum_even_odd([1, 2, 3, 4, 5]))  # (6, 9)


# 46. Convert a List to a String
# Problem: Convert a list of elements to a string.
def list_to_string(lst):
    return ''.join(str(x) for x in lst)

print(list_to_string([1, 2, 3]))  # "123"


# 47. Swap Two Variables
# Problem: Swap the values of two variables.
def swap(a, b):
    a, b = b, a
    return a, b

print(swap(5, 10))  # (10, 5)


# 48. Find the Missing Number in an Array of 1 to n
# Problem: Find the missing number in an array containing numbers from 1 to n.
def find_missing_number(arr, n):
    expected_sum = n * (n + 1) // 2
    actual_sum = sum(arr)
    return expected_sum - actual_sum

print(find_missing_number([1, 2, 4, 5], 5))  # 3


# 49. Check if a String Contains Only Digits
# Problem: Check if a string contains only digits.
def is_all_digits(s):
    return s.isdigit()

print(is_all_digits("123456"))  # True
print(is_all_digits("123a56"))  # False


# 50. Calculate the Power of a Number
# Problem: Calculate the power of a number raised to another number.
def power(base, exponent):
    return base ** exponent

print(power(2, 3))  # 8


# 51. Count the Occurrence of Each Element in a List
# Problem: Count the occurrence of each element in a list.
from collections import Counter
def count_occurrences(lst):
    return dict(Counter(lst))

print(count_occurrences([1, 2, 2, 3, 3, 3]))  # {1: 1, 2: 2, 3: 3}


# 52. Check for Perfect Number
# Problem: Check if a number is a perfect number.
def is_perfect_number(n):
    divisors_sum = sum(i for i in range(1, n) if n % i == 0)
    return divisors_sum == n

print(is_perfect_number(6))  # True
print(is_perfect_number(10))  # False


# 53. Convert a List of Strings to Uppercase
# Problem: Convert all strings in a list to uppercase.
def to_uppercase(lst):
    return [x.upper() for x in lst]

print(to_uppercase(["hello", "world"]))  # ['HELLO', 'WORLD']


# 54. Find GCD of Two Numbers
# Problem: Find the greatest common divisor (GCD) of two numbers.
import math
def find_gcd(a, b):
    return math.gcd(a, b)

print(find_gcd(56, 98))  # 14


# 55. Convert Binary to Decimal
# Problem: Convert a binary string to a decimal number.
def binary_to_decimal(binary_str):
    return int(binary_str, 2)

print(binary_to_decimal("1101"))  # 13


# 56. Find All Divisors of a Number
# Problem: Find all divisors of a number.
def divisors(n):
    return [i for i in range(1, n + 1) if n % i == 0]

print(divisors(28))  # [1, 2, 4, 7, 14, 28]


# 57. Find the Area of a Circle
# Problem: Calculate the area of a circle given its radius.
import math
def area_of_circle(radius):
    return math.pi * radius ** 2

print(area_of_circle(5))  # 78.53981633974483


# 58. Find the Sum of All Even Numbers Between 1 and N
# Problem: Find the sum of all even numbers between 1 and N.
def sum_of_even_numbers(n):
    return sum(i for i in range(1, n + 1) if i % 2 == 0)

print(sum_of_even_numbers(10))  # 30


# 59. Reverse Words in a Sentence
# Problem: Reverse the words in a sentence.
def reverse_words(sentence):
    return ' '.join(reversed(sentence.split()))

print(reverse_words("Hello World Python"))  # "Python World Hello"


# 60. Find the Most Frequent Element in a List
# Problem: Find the most frequent element in a list.
from collections import Counter
def most_frequent(lst):
    return Counter(lst).most_common(1)[0][0]

print(most_frequent([1, 2, 3, 2, 2, 3, 1]))  # 2


# 61. Count the Number of Vowels in a String
# Problem: Count the number of vowels in a string.
def count_vowels(s):
    return sum(1 for char in s.lower() if char in 'aeiou')

print(count_vowels("hello"))  # 2


# 62. Check if a String is an Anagram of Another String
# Problem: Check if one string is an anagram of another.
def are_anagrams(str1, str2):
    return sorted(str1) == sorted(str2)

print(are_anagrams("listen", "silent"))  # True


# 63. Find the LCM of Two Numbers
# Problem: Find the least common multiple (LCM) of two numbers.
def find_lcm(a, b):
    return abs(a * b) // math.gcd(a, b)

print(find_lcm(4, 5))  # 20


# 64. Check if a List Contains Duplicates
# Problem: Check if a list contains any duplicate elements.
def contains_duplicates(lst):
    return len(lst) != len(set(lst))

print(contains_duplicates([1, 2, 3, 4, 5]))  # False
print(contains_duplicates([1, 2, 3, 3, 5]))  # True


# 65. Calculate the Factorial of a Number Using Recursion
# Problem: Find the factorial of a number using recursion.
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)

print(factorial(5))  # 120


# 66. Sum of Odd Numbers in a List
# Problem: Find the sum of all odd numbers in a list.
def sum_of_odds(lst):
    return sum(x for x in lst if x % 2 != 0)

print(sum_of_odds([1, 2, 3, 4, 5]))  # 9


# 67. Check if a List is a Palindrome
# Problem: Check if a list is a palindrome.
def is_palindrome(lst):
    return lst == lst[::-1]

print(is_palindrome([1, 2, 3, 2, 1]))  # True
print(is_palindrome([1, 2, 3, 4]))  # False


# 68. Merge Two Dictionaries
# Problem: Merge two dictionaries into one.
def merge_dicts(dict1, dict2):
    dict1.update(dict2)
    return dict1

print(merge_dicts({'a': 1, 'b': 2}, {'c': 3, 'd': 4}))  # {'a': 1, 'b': 2, 'c': 3, 'd': 4}


# 69. Convert Decimal to Binary
# Problem: Convert a decimal number to binary.
def decimal_to_binary(decimal):
    return bin(decimal)[2:]

print(decimal_to_binary(13))  # "1101"


# 70. Find the Intersection of Two Lists
# Problem: Find the intersection (common elements) of two lists.
def list_intersection(lst1, lst2):
    return list(set(lst1) & set(lst2))

print(list_intersection([1, 2, 3, 4], [3, 4, 5, 6]))  # [3, 4]


# 71. Find the Sum of All Digits in a Number
# Problem: Find the sum of all digits in a number.
def sum_of_digits(n):
    return sum(int(digit) for digit in str(n))

print(sum_of_digits(12345))  # 15


# 72. Check if a Number is Prime
# Problem: Check if a number is prime.
def is_prime(n):
    if n < 2:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

print(is_prime(11))  # True
print(is_prime(12))  # False


# 73. Reverse a String Without Using Slicing
# Problem: Reverse a string without using slicing.
def reverse_string(s):
    reversed_str = ""
    for char in s:
        reversed_str = char + reversed_str
    return reversed_str

print(reverse_string("hello"))  # "olleh"


# 74. Find the Missing Number in a List of Consecutive Numbers
# Problem: Given a list of consecutive numbers, find the missing number.
def find_missing_number(lst):
    n = len(lst) + 1
    total_sum = n * (n + 1) // 2
    return total_sum - sum(lst)

print(find_missing_number([1, 2, 4, 5]))  # 3


# 75. Count the Number of Words in a Sentence
# Problem: Count the number of words in a sentence.
def word_count(sentence):
    return len(sentence.split())

print(word_count("This is a test sentence."))  # 5


# 76. Check if a Number is Armstrong
# Problem: Check if a number is an Armstrong number (e.g., 153 is Armstrong because 1^3 + 5^3 + 3^3 = 153).
def is_armstrong(n):
    digits = [int(digit) for digit in str(n)]
    power = len(digits)
    return n == sum(digit ** power for digit in digits)

print(is_armstrong(153))  # True
print(is_armstrong(123))  # False


# 77. Find the Most Common Character in a String
# Problem: Find the most common character in a string.
from collections import Counter
def most_common_char(s):
    return Counter(s).most_common(1)[0][0]

print(most_common_char("hello"))  # "l"


# 78. Convert a String to Title Case
# Problem: Convert a string to title case (capitalize the first letter of each word).
def title_case(s):
    return ' '.join(word.capitalize() for word in s.split())

print(title_case("hello world"))  # "Hello World"


# 79. Check if a Number is a Palindrome
# Problem: Check if a number is a palindrome.
def is_palindrome_number(n):
    return str(n) == str(n)[::-1]

print(is_palindrome_number(121))  # True
print(is_palindrome_number(123))  # False


# 80. Find the Length of the Longest Word in a Sentence
# Problem: Find the length of the longest word in a sentence.
def longest_word_length(sentence):
    words = sentence.split()
    return max(len(word) for word in words)

print(longest_word_length("This is an example sentence"))  # 8


# 81. Check if Two Strings Are Rotations of Each Other
# Problem: Check if two strings are rotations of each other.
def are_rotations(str1, str2):
    return len(str1) == len(str2) and str1 in (str2 + str2)

print(are_rotations("abc", "cab"))  # True
print(are_rotations("abc", "abcd"))  # False


# 82. Find the Union of Two Lists
# Problem: Find the union of two lists (combine without duplicates).
def list_union(lst1, lst2):
    return list(set(lst1) | set(lst2))

print(list_union([1, 2, 3], [3, 4, 5]))  # [1, 2, 3, 4, 5]


# 83. Count the Occurrence of Vowels in a String
# Problem: Count how many vowels are in a string.
def count_vowels_in_string(s):
    return sum(1 for char in s.lower() if char in 'aeiou')

print(count_vowels_in_string("hello"))  # 2


# 84. Calculate the Fibonacci Sequence Up to N
# Problem: Calculate the Fibonacci sequence up to the Nth term.
def fibonacci(n):
    fib = [0, 1]
    while len(fib) < n:
        fib.append(fib[-1] + fib[-2])
    return fib

print(fibonacci(7))  # [0, 1, 1, 2, 3, 5, 8]


# 85. Find the Smallest Element in a List
# Problem: Find the smallest element in a list.
def find_smallest(lst):
    return min(lst)

print(find_smallest([5, 2, 7, 1]))  # 1


# 86. Create a List of Prime Numbers Up to N
# Problem: Create a list of prime numbers up to N.
def prime_numbers_up_to(n):
    primes = []
    for i in range(2, n + 1):
        if is_prime(i):
            primes.append(i)
    return primes

print(prime_numbers_up_to(10))  # [2, 3, 5, 7]


# 87. Convert a List of Numbers to Strings
# Problem: Convert all numbers in a list to strings.
def numbers_to_strings(lst):
    return [str(x) for x in lst]

print(numbers_to_strings([1, 2, 3]))  # ['1', '2', '3']


# 88. Merge Two Sorted Lists
# Problem: Merge two sorted lists into one sorted list.
def merge_sorted_lists(lst1, lst2):
    return sorted(lst1 + lst2)

print(merge_sorted_lists([1, 3, 5], [2, 4, 6]))  # [1, 2, 3, 4, 5, 6]


# 89. Check if a String is a Pangram
# Problem: Check if a string is a pangram (contains every letter of the alphabet at least once).
import string
def is_pangram(s):
    return set(s.lower()) >= set(string.ascii_lowercase)

print(is_pangram("The quick brown fox jumps over the lazy dog"))  # True
print(is_pangram("Hello world"))  # False


# 90. Find the Common Elements Between Three Lists
# Problem: Find the common elements between three lists.
def common_elements(lst1, lst2, lst3):
    return list(set(lst1) & set(lst2) & set(lst3))

print(common_elements([1, 2, 3], [3, 4, 5], [5, 3, 6]))  # [3]

# 91. Find the Second Largest Number in a List
# Problem: Find the second largest number in a list.
def second_largest(lst):
    unique_lst = list(set(lst))
    unique_lst.sort()
    return unique_lst[-2] if len(unique_lst) > 1 else None

print(second_largest([1, 2, 3, 4, 5]))  # 4
print(second_largest([5, 5, 5]))  # None


# 92. Remove Duplicates from a List
# Problem: Remove duplicates from a list.
def remove_duplicates(lst):
    return list(set(lst))

print(remove_duplicates([1, 2, 3, 3, 4, 4, 5]))  # [1, 2, 3, 4, 5]


# 93. Count the Number of Even Numbers in a List
# Problem: Count the number of even numbers in a list.
def count_even_numbers(lst):
    return sum(1 for num in lst if num % 2 == 0)

print(count_even_numbers([1, 2, 3, 4, 5]))  # 2


# 94. Find the Sum of Even and Odd Numbers Separately in a List
# Problem: Find the sum of even and odd numbers separately in a list.
def sum_even_odd(lst):
    even_sum = sum(num for num in lst if num % 2 == 0)
    odd_sum = sum(num for num in lst if num % 2 != 0)
    return even_sum, odd_sum

print(sum_even_odd([1, 2, 3, 4, 5]))  # (6, 9)


# 95. Check if a String Contains Only Digits
# Problem: Check if a string contains only digits.
def is_digit(s):
    return s.isdigit()

print(is_digit("12345"))  # True
print(is_digit("abc123"))  # False


# 96. Find the Intersection of Two Lists
# Problem: Find the intersection of two lists.
def list_intersection(lst1, lst2):
    return list(set(lst1) & set(lst2))

print(list_intersection([1, 2, 3], [3, 4, 5]))  # [3]


# 97. Find the Maximum Occurrence Character in a String
# Problem: Find the character that occurs the maximum number of times in a string.
from collections import Counter
def max_occurrence_char(s):
    count = Counter(s)
    return count.most_common(1)[0][0]

print(max_occurrence_char("hello"))  # "l"


# 98. Convert a List of Strings to Uppercase
# Problem: Convert a list of strings to uppercase.
def convert_to_uppercase(lst):
    return [s.upper() for s in lst]

print(convert_to_uppercase(["hello", "world"]))  # ['HELLO', 'WORLD']


# 99. Calculate the Average of Numbers in a List
# Problem: Calculate the average of numbers in a list.
def average(lst):
    return sum(lst) / len(lst) if lst else 0

print(average([1, 2, 3, 4, 5]))  # 3.0


# 100. Find the Unique Elements from Three Lists
# Problem: Find the unique elements from three lists.
def unique_elements(lst1, lst2, lst3):
    return list(set(lst1) ^ set(lst2) ^ set(lst3))

print(unique_elements([1, 2, 3], [3, 4, 5], [5, 6, 7]))  # [1, 2, 4, 6, 7]


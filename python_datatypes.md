Python Data Types 
Python has several built-in data types. These data types define the type of value a variable can hold.

🔹 1. Numeric Data Types
1.1 Integer (int)
Represents whole numbers (positive or negative).
age = 20
count = -5
1.2 Float (float)
Represents decimal numbers.
pi = 3.14
marks = 89.5
1.3 Complex (complex)
Numbers with real + imaginary part.
z = 2 + 3j

🔹 2. String Data Type
str — String
A sequence of characters enclosed in quotes.
name = "Riya"
message = 'Hello Python'
Strings are immutable, meaning they cannot be changed after creation.

🔹 3. Boolean Data Type
bool — Boolean
Represents either True or False.
is_student = True
is_logged_in = False

🔹 4. Sequence Data Types
4.1 List (list)
Ordered, changeable (mutable), allows duplicates.
fruits = ["apple", "banana", "mango"]
4.2 Tuple (tuple)
Ordered, unchangeable, allows duplicates.
colors = ("red", "green", "blue")
4.3 Range (range)
Used for generating sequences of numbers (mostly in loops).
numbers = range(1, 10)

🔹 5. Set Data Types
5.1 Set (set)
Unordered, no duplicates allowed.
unique_numbers = {1, 2, 3, 3}
5.2 Frozen Set (frozenset)
Same as set but immutable.
constant_set = frozenset([1, 2, 3])

🔹 6. Mapping Data Type
dict — Dictionary
Stores data in key–value pairs.
student = {
    "name": "Riya",
    "course": "Computer Science"
}

🔹 7. Binary Data Types
7.1 Bytes (bytes)
Immutable sequence of bytes.
data = b"hello"
7.2 Bytearray (bytearray)
Mutable version of bytes.
arr = bytearray([1, 2, 3])
7.3 Memoryview (memoryview)
Used to access binary data without copying.
mv = memoryview(b"ABC")

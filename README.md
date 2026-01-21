# Experiment-2A
# Aim- Study of List
# Theory
In Python, a list is a built-in data structure used to store multiple items in a single variable. It is ordered, mutable (changeable), and can contain different data types. Elements can be duplicated in the list.
1. Creating list- To create a list we use square brackets. Example- numbers=[1,2,3,4,5].
2. Accessing list- print(name_of_the_list). Example- print(numbers[4])-will give 5th element of list as indexing starts from 0.
3. Accessing elements of list- To print only a particular elemnet. Example- numbers.
4. Lenght of the list- To find the number of elements present in the list is the lenght of the list. Example- print(len(numbers)).
5. Slicing in python- List slicing in Python is used to extract a part from a list.
   Syntax- List[start:end:step]
   | Expression   | Result              |
   | ------------ | ------------------- |
   | numbers[:]`    | Full list           |
   | numbers[:3]`   | First 3 elements    |
   | numbers[3:]`   | From index 3 to end |
   | numbers[-3:]`  | Last 3 elements     |
   | numbers[::2]`  | Every 2nd element   |
   | numbers[::-1]` | Reverse list        |
6. Adding element in the list using append- To add a element at the back we use append. Example- numbers.append(6).
7. Adding element in the list using slicing- To add a element at a particular position we type its index also and use insert. Example- numbers.insert(1,6).
8. Replacing an element-To replace one element by another.Example- numbers[1]=6.
9. Combining two list- Two lists can be combined by using extend. Example- list1.extend(list2).
10. Removing the element from the list- Example- numbers.remove(3).
11. Sorting the list- Example- names.sort().
12. Other operations in list- max()- gives the maximum value from the elements of the list, min()-gives the minimum value from the elements of the list, sum()-  gives the total sum of the elements.
# Algorithm-1 
1. Start
2. Creating a list of student names and displaying it
3. Displaying the first and last name
4. Removing one name from the list and diaplsying list
5. Sorting the names and printing the list
6. End
# Algorithm-2
1. Start
2. Creating a list of student's marks and printing it
3. displaying the highest and lowest marks using max() and min()
4. Calcuculating average marks by calculating the sum and then the lenght of the list and diplaying it
5. Sorting the marks and displaying the updated list
6. End
# Conclusion
A list in Python is one of the most important and commonly used data structures.Lists can hold different types of data and support many operations such as indexing, slicing, adding, removing, and modifying elements. Because of their flexibility, simplicity, and wide range of built-in methods, lists are very useful for tasks like data storage, processing, and iteration. Overall, lists make programming easier and more efficient when working with collections of data.

# CSCD300Lab1

Purpose

The purpose of this assignment is to allow you to demonstrate basic knowledge of linked lists and exceptions.  These operations include (directly or indirectly): inserting, deleting, finding and modifying and "printing."  This assignment should be done by you without outside help (other than from your instructor). If you are unable to complete this assignment in the allotted time, it is a strong indication you are not ready for the material in this class and you MUST meet with the instructor to discuss your continued enrollment in the class.

Specifics

•	As defined in the MyLinkedList  class, you have to use a dummy node for your singly LinkedList -- this will actually simplify the amount of code you need for many operations.
•	Please implement all the methods in the MyLinkedList class except for the AddFirst()  and toString() methods. The requirements and specifications for each method are provided in the comments above each method header. 
•	Please do NOT change the interface and signature (the list of arguments and their type, and return type) of the methods in the MyLinkedList class.
•	Please do NOT change the provided AddFirst() and toString() methods in the MyLinkedList class.
•	Please do NOT change any code in the provided MyLinkedListTester class. However, during your testing and debugging, you can comment out some method calls in the main() of MyLinkedListTester class in order to single out the method that you are currently debugging. After finish debugging, please make sure all methods are called (uncommented) in the main() of MyLinkedListTester class, as it was initially provided by the instructor. 
•	Please read and understand the design and implementation of the MyLinkedListTester class. So that you can imitate its design in other project when testing each method of your implementation. 

List of methods you have to implement
1.	public Object removeFirst() throws Exception
2.	public boolean contains(Object o)
3.	public boolean remove(Object o)
4.	public boolean removeAllCopies( Object o )
5.	public static MyLinkedList interleave(MyLinkedList A, MyLinkedList B)
6.	public void add(int index, Object o)
7.	public Object get(int index)
8.	public Object remove(int index) throws IndexOutOfBoundsException 
9.	public boolean add(Object e)

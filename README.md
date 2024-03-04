# Day14-with-java

Today learned about strings.

Definition of string: String is a series of characters enclosed within double quotes.

In java, strings are classified into two types. They are mutable(changeble) and immutable(unchangeble) strings.

Basically there are 3 different ways to create immutable strings.

1. By using class name. Ex: String s=new String("WELCOME");

2. By using reference. Ex: String s="WELCOME";

3. By writting array of characters then convert to String. Ex: char[] c={'W', 'E', 'L', 'C', 'O', 'M', 'E'}; String s=new String(c);

Finally we can create a immutable string using new keyword or without using new keyword.

If we take new then JVM get activated.

Different ways to compare strings.


1. using an operator (==), Strings are compared based on reference.

2. Using equals() method, Strings are compared based on values.

3. using compareTo() method, Strings are compared character by character.

4. using equalsIgnoreCase() method, Strings are compared by ignoring case.

Strings are objects, objects are all allocated memory in heap segment. so strings are stored in heap segment.

Inside Heap segment for strings to be created there is a special region created called as String pool. This String pool again divided into two parts they are CONSTANT Pool and NON CONSTANT Pool. 

When Strings are created without using new keyword, they will be in CONSTANT Pool.  In CONSTANT Pool, duplicates are not allowed. Whereas Strings which were created using new keyword are under NON CONSTANT Pool. In NON CONSTANT Pool, duplicates are allowed.

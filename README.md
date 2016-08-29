Aqui estão as questoes de 1 a 50, das 147, com suas opções e a resposta correta


#### Question No: 1

Given:

```java
1. public class test (
2.  public static void main (String args[]) {
3.    int i = 0xFFFFFFF1;
4.    int j = ~i;
5.
6.  }
7. )
```

**What is the decimal value of j at line 5?**
* A. 0
* B. 1
* C. 14
* D. –15
* E. An error at line 3 causes compilation to fail.
* F. An error at line 4 causes compilation to fail.

_Answer: C_

#### Question No: 2

Given:

```java
Integer i = new Integer (42);
Long 1 = new Long (42);
Double d = new Double (42.0);
```

**Which two expressions evaluate to True? (Choose Two)**

* A. (i ==1)
* B. (i == d)
* C. (d == 1)
* D. (i.equals (d))
* E. (d.equals (i))
* F. (i.equals (42))

_Answer: D, E_

#### Question No: 3

**Exhibit :**

```java
1. public class test (
2. private static int j = 0;
3.
4. private static boolean methodB(int k) (
5. j += k;
6. return true;
6. )
7.
8. public static void methodA(int i) {
9. boolean b:
10. b = i < 10 | methodB (4);
11. b = i < 10 || methodB (8);
12. )
13.
14. public static void main (String args[] } (
15. methodA (0);
16. system.out.printIn(j);
17. )
18. )
```

**What is the result?**

* A. The program prints “0”
* B. The program prints “4”
* C. The program prints “8”
* D. The program prints “12”
* E. The code does not complete.

_Answer: B_

#### Question No: 4

Given
1. Public class test (
2. Public static void main (String args[]) (
3. System.out.printIn (6 ^ 3);
4. )
5. )
What is the output?
Answer: 5

#### Question No: 5

Given:
1. public class Foo {
2. public static void main (String [] args) {
3. StringBuffer a = new StringBuffer (“A”);
4. StringBuffer b = new StringBuffer (“B”);
5. operate (a,b);
6. system.out.printIn{a + “,” +b};
7. )
8. static void operate (StringBuffer x, StringBuffer y) {
9. x.append {y};
10. y = x;
11. )
12. }
What is the result?
A. The code compiles and prints “A,B”.
B. The code compiles and prints “A,A”.
C. The code compiles and prints “B,B”.
D. The code compiles and prints “AB,B”.
E. The code compiles and prints “AB,AB”.
F. The code does not compile because “+” cannot be overloaded for StringBuffer.
Answer: D

#### Question No: 6
Exhibit:
1. Public class test (
2. Public static void stringReplace (String text) (
3. Text = text.replace (‘j’ , ‘i’);
4. )
5.
6. public static void bufferReplace (StringBuffer text) (
7. text = text.append (“C”)
8. )
9.
10. public static void main (String args[]} (
11. String textString = new String (“java”);
12. StringBuffer text BufferString = new StringBuffer (“java”);
13.
14. stringReplace (textString);
15. BufferReplace (textBuffer);
16.
17. System.out.printIn (textString + textBuffer);
18. }
19. )
What is the output?
Answer: JAVAJAVA

#### Question No: 7
Exhibit:
1. public class test {
2. public static void add3 (Integer i) }
3. int val = i.intValue ( );
4. val += 3;
5. i = new Integer (val);
6. }
7.
8. public static void main (String args [ ] ) {
9. Integer i = new Integer (0);
10. add3 (i);
11. system.out.printIn (i.intValue ( ) );
12. }
13. )
What is the result?
A. Compilation will fail.
B. The program prints “0”.
C. The program prints “3”.
D. Compilation will succeed but an exception will be thrown at line 3.
Answer: B

#### Question No: 8
Given:
1. public class ConstOver {
2. public ConstOver (int x, int y, int z) {
3. }
4. }
Which two overload the ConstOver constructor? (Choose Two)
A. ConstOver ( ) { }
B. Protected int ConstOver ( ) { }
C. Private ConstOver (int z, int y, byte x) { }
D. Public Object ConstOver (int x, int y, int z) { }
E. Public void ConstOver (byte x, byte y, byte z) { }
Answer: A, C

#### Question No: 9
Given:
1. public class MethodOver {
2. public void setVar (int a, int b, float c) {
3. }
4. }
Which two overload the setVar method? (Choose Two)
A. Private void setVar (int a, float c, int b) { }
B. Protected void setVar (int a, int b, float c) { }
C. Public int setVar (int a, float c, int b) (return a;)
D. Public int setVar (int a, int b, float c) (return a;)
E. Protected float setVar (int a, int b, float c) (return c;)
Answer: A, C

#### Question No: 10
Given:
1. class BaseClass {
2. Private float x = 1.0f ;
3. protected float getVar ( ) ( return x;)
4. }
5. class Subclass extends BaseClass (
6. private float x = 2.0f;
7. //insert code here
8. )
Which two are valid examples of method overriding? (Choose Two)
A. Float getVar ( ) { return x;}
B. Public float getVar ( ) { return x;}
C. Float double getVar ( ) { return x;}
D. Public float getVar ( ) { return x;}
E. Public float getVar (float f ) { return f;}
Answer: B, D

#### Question No: 11
Which two demonstrate an “is a” relationship? (Choose Two)
A. public interface Person { }
public class Employee extends Person { }
B. public interface Shape { }
public class Employee extends Shape { }
C. public interface Color { }
public class Employee extends Color { }
D. public class Species { }
public class Animal (private Species species;)
E. interface Component { }
Class Container implements Component (
Private Component[ ] children;
)
Answer: D, E

#### Question No: 12
Which statement is true?
A. An anonymous inner class may be declared as final.
B. An anonymous inner class can be declared as private.
C. An anonymous inner class can implement multiple interfaces.
D. An anonymous inner class can access final variables in any enclosing scope.
E. Construction of an instance of a static inner class requires an instance of the enclosing outer class.
Answer: D

#### Question No 13
Given:
1. package foo;
2.
3. public class Outer (
4. public static class Inner (
5. )
6. )
Which statement is true?
A. An instance of the Inner class can be constructed with “new Outer.Inner ()”
B. An instance of the inner class cannot be constructed outside of package foo.
C. An instance of the inner class can only be constructed from within the outer class.
D. From within the package bar, an instance of the inner class can be constructed with “new inner()”
Answer: A

#### Question No 14
Exhibit:
1. public class enclosingone (
2. public class insideone{}
3. )
4. public class inertest(
5. public static void main (string[]args)(
6. enclosingone eo= new enclosingone ();
7. //insert code here
8. )
9. )
Which statement at line 7 constructs an instance of the inner class?
A. InsideOnew ei= eo.new InsideOn();
B. Eo.InsideOne ei = eo.new InsideOne();
C. InsideOne ei = EnclosingOne.new InsideOne();
D. EnclosingOne.InsideOne ei = eo.new InsideOne();
Answer: D

#### Question No 15
Exhibit:
1. interface foo {
2. int k = 0;
3. ]
4.
5. public class test implements Foo (
6. public static void main(String args[]) (
7. int i;
8. Test test = new test ();
9. i= test.k;
10.i= Test.k;
11.i= Foo.k;
12.)
13.)
14.
What is the result?
A. Compilation succeeds.
B. An error at line 2 causes compilation to fail.
C. An error at line 9 causes compilation to fail.
D. An error at line 10 causes compilation to fail.
E. An error at line 11 causes compilation to fail.
Answer: A

#### Question No 16
Given:
1. //point X
2. public class foo (
3. public static void main (String[]args) throws Exception {
4. printWriter out = new PrintWriter (new
5. java.io.outputStreamWriter (System.out), true;
6. out.printIn(“Hello”);
7. }
8. )
Which statement at PointX on line 1 allows this code to compile and run?
A. Import java.io.PrintWriter;
B. Include java.io.PrintWriter;
C. Import java.io.OutputStreamWriter;
D. Include java.io.OutputStreamWriter;
E. No statement is needed.
Answer: A

#### Question No 17
Which two statements are reserved words in Java? (Choose Two)
A. Run
B. Import
C. Default
D. Implement
Answer: B, C

#### Question No 18
Which three are valid declarations of a float? (Choose Three)
A. Float foo = -1;
B. Float foo = 1.0;
C. Float foo = 42e1;
D. Float foo = 2.02f;
E. Float foo = 3.03d;
F. Float foo = 0x0123;
Answer: A, D, F

#### Question No 19
Given:
8. int index = 1;
9. boolean[] test = new Boolean[3];
10. boolean foo= test [index];
What is the result?
A. Foo has the value of 0.
B. Foo has the value of null.
C. Foo has the value of true.
D. Foo has the value of false.
E. An exception is thrown.
F. The code will not compile.
Answer: D

#### Question No 20
Given:
1. public class test(
2. public static void main(string[]args){
3. string foo = args [1];
4. string foo = args [2];
5. string foo = args [3];
6. }
7. }
And command line invocation:
Java Test red green blue
What is the result?
A. Baz has the value of “”
B. Baz has the value of null
C. Baz has the value of “red”
D. Baz has the value of “blue”
E. Bax has the value of “green”
F. The code does not compile.
G. The program throws an exception.
Answer: G

#### Question No 21
Given:
8. int index = 1;
9. int [] foo = new int [3];
10.int bar = foo [index];
11.int baz = bar + index;
What is the result?
A. Baz has the value of 0
B. Baz has the value of 1
C. Baz has the value of 2
D. An exception is thrown.
E. The code will not compile.
Answer: B

#### Question No 22
Given:
1. public class foo {
2. public static void main (String[]args) {
3. String s;
4. system.out.printIn (“s=” + s);
5. }
6. }
What is the result?
A. The code compiles and “s=” is printed.
B. The code compiles and “s=null” is printed.
C. The code does not compile because string s is not initialized.
D. The code does not compile because string s cannot be referenced.
E. The code compiles, but a NullPointerException is thrown when toString is called.
Answer: C

#### Question No 23
Which will declare a method that forces a subclass to implement it?
A. Public double methoda();
B. Static void methoda (double d1) {}
C. Public native double methoda();
D. Abstract public void methoda();
E. Protected void methoda (double d1){}
Answer: D

#### Question No 24
You want subclasses in any package to have access to members of a superclass. Which is the most
restrictive access modifier that will accomplish this objective?
A. Public
B. Private
C. Protected
D. Transient
E. No access modifier is qualified
Answer: C

#### Question No 25
Given:
1. abstract class abstrctIt {
2. abstract float getFloat ();
3. )
4. public class AbstractTest extends AbstractIt {
5. private float f1= 1.0f;
6. private float getFloat () {return f1;}
7. }
What is the result?
A. Compilation is successful.
B. An error on line 6 causes a runtime failure.
C. An error at line 6 causes compilation to fail.
D. An error at line 2 causes compilation to fail.
Answer: C

#### Question No 26
Exhibit:
1. public class test(
2. public int aMethod()[
3. static int i=0;
4. i++;
5. return I;
6. )
7. public static void main (String args[]){
8. test test = new test();
9. test.aMethod();
10.int j = test.aMethod();
11.System.out.printIn(j);
12.]
13.}
What is the result?
A. Compilation will fail.
B. Compilation will succeed and the program will print “0”
C. Compilation will succeed and the program will print “1”
D. Compilation will succeed and the program will print “2”
Answer: D

#### Question No 27
Given:
1. class super {
2. public float getNum() {return 3.0f;}
3. )
4.
5. public class Sub extends Super {
6.
7. )
Which method, placed at line 6, will cause a compiler error?
A. Public float getNum() {return 4.0f; }
B. Public void getNum () { }
C. Public void getNum (double d) { }
D. Public double getNum (float d) {retrun 4.0f; }
Answer: B

#### Question No 28
Which declaration prevents creating a subclass of an outer class?
A. Static class FooBar{}
B. Private class FooBar{}
C. Abstract public class FooBar{}
D. Final public class FooBar{}
E. Final abstract class FooBar{}
Answer: D

#### Question No 29
Given:
1. byte [] arry1, array2[];
2. byte array3 [][];
3. byte[][] array4;
If each array has been initialized, which statement will cause a compiler error?
A. Array2 = array1;
B. Array2 = array3;
C. Array2 = array4;
D. Both A and B
E. Both A and C
F. Both B and C
Answer: F

#### Question No 30
Exhibit:
1. class super (
2. public int I = 0;
3.
4. public super (string text) (
5. I = 1
6. )
7. )
8.
9. public class sub extends super (
10. public sub (string text) (
11. i= 2
12. )
13.
14. public static void main (straing args[]) (
15. sub sub = new sub (“Hello”);
16. system.out. PrintIn(sub.i);
17. )
18. )
What is the result?
A. Compilation will fail.
B. Compilation will succeed and the program will print “0”
C. Compilation will succeed and the program will print “1”
D. Compilation will succeed and the program will print “2”
Answer: A

#### Question No 31
Given:
1. public class returnIt (
2. returnType methodA(byte x, double y) (
3. return (short) x/y * 2;
4. )
5. )
What is the valid returnType for methodA in line 2?
A. Int
B. Byte
C. Long
D. Short
E. Float
F. Double
Answer: F

#### Question No 32
Given the ActionEvent, which method allows you to identify the affected component?
A. GetClass.
B. GetTarget.
C. GetSource.
D. GetComponent.
E. GetTargetComponent.
Answer: C

Question No 33
Which is a method of the MouseMotionListener interface?
A. Public void mouseMoved(MouseEvent)
B. Public boolean mouseMoved(MouseEvent)
C. Public void mouseMoved(MouseMotionEvent)
D. Public boolean MouseMoved(MouseMotionEvent)
E. Public boolean mouseMoved(MouseMotionEvent)
Answer: A

#### Question No 34
Exhibit:
1. import java.awt*;
2.
3. public class X extends Frame (
4. public static void main(string []args) (
5. X x = new X ();
6. X.pack();
7. x.setVisible(true);
8. )
9.
10. public X () (
11. setlayout (new GridLayout (2,2));
12.
13. Panel p1 = new panel();
14. Add(p1);
15. Button b1= new Button (“One”);
16. P1.add(b1);
17.
18. Panel p2 = new panel();
19. Add(p2);
20. Button b2= new Button (“Two”);
21. P2.add(b2);
22.
23. Button b3= new Button (“Three”);
24. add(b3);
25.
26. Button b4= new Button (“Four”);
27. add(b4);
28. )
29. )
Which two statements are true? (Choose Two)
A. All the buttons change height if the frame height is resized.
B. All the buttons change width if the Frame width is resized.
C. The size of the button labeled “One” is constant even if the Frame is resized.
D. Both width and height of the button labeled “Three” might change if the Frame is resized.
Answer: C, D

#### Question No 35
You are assigned the task of building a panel containing a TextArea at the top, a label directly below it,
and a button directly below the label. If the three components are added directly to the panel. Which
layout manager can the panel use to ensure that the TextArea absorbs all of the free vertical space when
the panel is resized?
A. GridLayout.
B. CardLayout.
C. FlowLayout.
D. BorderLayout.
E. GridBagLayout.
Answer: E

#### Question No 36
Which gets the name of the parent directory file “file.txt”?
A. String name= File.getParentName(“file.txt”);
B. String name= (new File(“file.txt”)).getParent();
C. String name = (new File(“file.txt”)).getParentName();
D. String name= (new File(“file.txt”)).getParentFile();
E. Directory dir=(new File (“file.txt”)).getParentDir();
String name= dir.getName();
Answer: B

#### Question No 37
Which can be used to encode charS for output?
A. Java.io.OutputStream.
B. Java.io.OutputStreamWriter.
C. Java.io.EncodeOutputStream.
D. Java.io.EncodeWriter.
E. Java.io.BufferedOutputStream.
Answer: B

#### Question No 38
The file “file.txt” exists on the file system and contsins ASCII text.
Given:
38. try {
39. File f = new File(“file.txt”);
40. OutputStream out = new FileOutputStream(f, true);
41. }
42. catch (IOException) {}
What is the result?
A. The code does not compile.
B. The code runs and no change is made to the file.
C. The code runs and sets the length of the file to 0.
D. An exception is thrown because the file is not closed.
E. The code runs and deletes the file from the file system.
Answer: A

#### Question No 39
Which constructs a DataOutputStream?
A. New dataOutputStream(“out.txt”);
B. New dataOutputStream(new file(“out.txt”));
C. New dataOutputStream(new writer(“out.txt”));
D. New dataOutputStream(new FileWriter(“out.txt”));
E. New dataOutputStream(new OutputStream(“out.txt”));
F. New dataOutputStream(new FileOutputStream(“out.txt”));
Answer: F

#### Question No 40
What writes the text “<end>” to the end of the file “file.txt”?
A. OutputStream out= new FileOutputStream (“file.txt”);
Out.writeBytes (“<end>/n”);
B. OutputStream os= new FileOutputStream (“file.txt”, true);
DataOutputStream out = new DataOutputStream(os);
out.writeBytes (“<end>/n”);
310-025
Leading the way in IT testing and certification tools, www.testking.com
- 23 -
C. OutputStream os= new FileOutputStream (“file.txt”);
DataOutputStream out = new DataOutputStream(os);
out.writeBytes (“<end>/n”);
D. OutputStream os= new OutputStream (“file.txt”, true);
DataOutputStream out = new DataOutputStream(os);
out.writeBytes (“<end>/n”);
Answer: B

#### Question No 41
Given:
1. public class X (
2. public object m () {
3. object o = new float (3.14F);
4. object [] oa = new object [1];
5. oa[0]= o;
6. o = null;
7. return oa[0];
8. }
9. }
When is the float object created in line 3, eligible for garbage collection?
A. Just after line 5
B. Just after line 6
C. Just after line 7 (that is, as the method returns)
D. Never in this method.
Answer: D

#### Question No 42
Given:
3. string foo = “ABCDE”;
4. foo.substring(3);
5. foo.concat(“XYZ”);
6.
Type the value of foo at line 6.
Answer: ABCDE

#### Question No 43
Which method is an appropriate way to determine the cosine of 42 degrees?
A. Double d = Math.cos(42);
B. Double d = Math.cosine(42);
C. Double d = Math.cos(Math.toRadians(42));
D. Double d = Math.cos(Math.toDegrees(42));
E. Double d = Math.cosine(Math.toRadians(42));
Answer: C

#### Question No 44
You need to store elements in a collection that guarantees that no duplicates are stored and all elements
can be accessed in natural order. Which interface provides that capability?
A. Java.util.Map.
B. Java.util.Set.
C. Java.util.List.
D. Java.util.StoredSet.
E. Java.util.StoredMap.
F. Java.util.Collection.
Answer: D

#### Question No 45
Which statement is true for the class java.util.HashSet?
A. The elements in the collection are ordered.
B. The collection is guaranteed to be immutable.
C. The elements in the collection are guaranteed to be unique.
D. The elements in the collection are accessed using a unique key.
E. The elements in the collections are guaranteed to be synchronized.
Answer: C

#### Question No 46
Given:
1. public class IfTest (
2. public static void main(string[]args) {
3. int x = 3;
4. int y = 1;
5. if (x = y)
6. system.out.printIn(“Not equal”);
7. else
8. system.out.printIn(“Equal”);
9. }
10. )
What is the result?
A. The output is “Equal”
B. The output in “Not Equal”
C. An error at line 5 causes compilation to fall.
D. The program executes but does not print a message.
Answer: C

#### Question No 47
Exhibit:
1. public class test (
2. public static void main(string args[]) {
3. int 1= 0;
4. while (i) {
5. if (i==4) {
6. break;
7. )
8. ++i;
9. )
10.
11. )
12. )
What is the value of i at line 10?
A. 0
B. 3
C. 4
D. 5
E. The code will not compile.
Answer: E

#### Question No 48
Given:
3. int i= 1, j= 10 ;
4. do (
5. if (i++> --j) continue;
6. ) while (i<5);
After execution, what are the values for I and j?
A. i = 6 and j= 5
B. i = 5 and j= 5
C. i = 6 and j= 4
D. i = 5 and j= 6
E. i = 6 and j= 6
Answer: D

#### Question No 49
Given:
1. switch (i) {
2. default:
3. System.out.printIn(“Hello”);
4. )
What are the two acceptable types for the variable i? (Choose Two)
A. Char
B. Byte
C. Float
D. Double
E. Object
Answer: A, B

#### Question No 50
Given:
1. public class foo {
2. public static void main (string[]args)
3. try {return;}
4. finally {system.out.printIn(“Finally”);}
5. }
6. )
What is the result?
A. The program runs and prints nothing.
B. The program runs and prints “Finally”
C. The code compiles, but an exception is thrown at runtime.
D. The code will not compile because the catch block is missing.
Answer: B

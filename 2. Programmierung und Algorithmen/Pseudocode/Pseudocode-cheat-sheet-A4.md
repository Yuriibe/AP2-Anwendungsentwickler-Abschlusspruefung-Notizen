**What is pseudocode?**

Pseudo-code is an alternative method of describing an algorithm that
uses text instead of a diagram.

Pseudo-code can be thought of as a simplified form of programming code.

The prefix 'pseudo' means 'false' or 'not genuine'.

Writing pseudo code allows us to lay down the logic of a problem in a
"almost like real code" way without having to worry about the actual
strict rules and syntax of a particular language.

**So what is this cheat sheet?**

This cheat sheet provides advice on the format in which you should write
pseudocode when answering OCR exam questions. Practice makes perfect.
Throughout your course practice producing pseudocode before you code up
solutions to problems and it will become second nature in the exam.

**Rules for writing pseudo-code**

By definition, there are no hard and fast rules for writing pseudo-code,
but certain guidelines will ensure that the algorithm is clear:

- Describe each step of the algorithm as briefly as possible.

- Use uppercase letters with keywords and other parts of the pseudo-code
  which are closer to a programming language.

- User lowercase letters with parts of the pseudo-code which are closer
  to English.

- If you use keywords to show the beginning and end of a block of code,
  then the code inside the block should be indented.

- Numbered or bulleted lists written in English is NOT enough for
  A'Level exams!

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 36%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Concept</th>
<th>Example Pseudocode</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td rowspan="2">Variables</td>
<td><p>x=3</p>
<p>name="Bob"</p></td>
<td>Variables are assigned using the = operator</td>
</tr>
<tr class="even">
<td>global userid = 123</td>
<td><p>Variables declared inside a function or procedure are assumed to
be local to that subroutine.</p>
<p>Variables in the main program can be made global with the keyword
global.</p></td>
</tr>
<tr class="odd">
<td>Casting</td>
<td><p>str(3) returns "3"</p>
<p>int("3") returns 3</p>
<p>float("3.14") returns 3.14</p></td>
<td>Variables should be typecast using the int, str, and float
functions.</td>
</tr>
<tr class="even">
<td>Outputting to screen</td>
<td>PRINT("hello")</td>
<td>PRINT(string)</td>
</tr>
<tr class="odd">
<td>Taking input from user</td>
<td>name = INPUT("Please enter your name")</td>
<td><em>Variable</em> = INPUT(<em>prompt to user</em>)</td>
</tr>
<tr class="even">
<td>Iteration – Count controlled</td>
<td><p>FOR I = 0 to 7</p>
<p>PRINT("Hello")</p>
<p>NEXT i</p></td>
<td>This would print hello 8 times (0-7 inclusive).</td>
</tr>
<tr class="odd">
<td rowspan="2">Iteration – Condition controlled</td>
<td><p>WHILE answer != "computer”</p>
<p>answer = INPUT("What is the password?")</p>
<p>ENDWHILE</p></td>
<td>While Loop</td>
</tr>
<tr class="even">
<td><p>DO</p>
<p>Answer = INPUT("What is the password?")</p>
<p>UNTIL answer == "computer"</p></td>
<td>Do Until Loop</td>
</tr>
<tr class="odd">
<td>Logical operators</td>
<td>WHILE x &lt;=5 AND flag == FALSE</td>
<td>AND OR NOT</td>
</tr>
<tr class="even">
<td rowspan="6">Comparison operators</td>
<td>==</td>
<td>Equal to</td>
</tr>
<tr class="odd">
<td>!=</td>
<td>Not equal to</td>
</tr>
<tr class="even">
<td>&lt;</td>
<td>Less than</td>
</tr>
<tr class="odd">
<td>&lt;=</td>
<td>Less than or equal to</td>
</tr>
<tr class="even">
<td>&gt;</td>
<td>Greater than</td>
</tr>
<tr class="odd">
<td>&gt;=</td>
<td>Greater than or equal to</td>
</tr>
<tr class="even">
<td rowspan="7">Arithmetic operators</td>
<td>+</td>
<td>Addition e.g. x=6+5 gives 11</td>
</tr>
<tr class="odd">
<td>-</td>
<td>Subtraction e.g. x=6-5 gives 1</td>
</tr>
<tr class="even">
<td>*</td>
<td>Multiplication e.g. x=12*2 gives 24</td>
</tr>
<tr class="odd">
<td>/</td>
<td>Division e.g. x=12/2 gives 6</td>
</tr>
<tr class="even">
<td>MOD</td>
<td>Modulus e.g. 12MOD5 gives 2</td>
</tr>
<tr class="odd">
<td>DIV</td>
<td>Quotient e.g. 17DIV5 gives 3</td>
</tr>
<tr class="even">
<td>^</td>
<td>Exponentiation e.g. 3^4 gives 81</td>
</tr>
</tbody>
</table>

**  
**

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 41%" />
<col style="width: 45%" />
</colgroup>
<thead>
<tr class="header">
<th>Concept</th>
<th>Example Pseudocode</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td rowspan="2">Selection</td>
<td><p>IF entry == "a" THEN</p>
<p>PRINT("You selected A")</p>
<p>ELSEIF entry == "b" then</p>
<p>PRINT("You selected B")</p>
<p>ELSE</p>
<p>PRINT("Unrecognised selection")</p>
<p>ENDIF</p></td>
<td>IF / ELSE selection</td>
</tr>
<tr class="even">
<td><p>SWITCH ENTRY:</p>
<p>CASE "A":</p>
<p>PRINT("You selected A")</p>
<p>CASE "B":1</p>
<p>PRINT("You selected B")</p>
<p>DEFAULT:</p>
<p>PRINT("Unrecognised selection")</p>
<p>ENDSWITCH</p></td>
<td>SWITCH / CASE selection</td>
</tr>
<tr class="odd">
<td rowspan="2">String handling</td>
<td>stringname.LENGTH</td>
<td>To get the length of a string</td>
</tr>
<tr class="even">
<td>stringname.SUBSTRING(startingPosition, numberOfCharacters)</td>
<td>To get a substring</td>
</tr>
<tr class="odd">
<td rowspan="3">Subroutines</td>
<td><p>FUNCTION triple(number)</p>
<p>RETURN number * 3</p>
<p>ENDFUNCTION</p>
<p>Called from main program</p>
<p>Y =triple(7)</p></td>
<td>Function</td>
</tr>
<tr class="even">
<td><p>PROCEDURE greeting(name)</p>
<p>PRINT("hello" + name)</p>
<p>ENDPROCEDURE</p>
<p>Called from main program</p>
<p>greeting("Hamish")</p></td>
<td>Procedure</td>
</tr>
<tr class="odd">
<td><p>PROCEDURE foobar(x:<strong>byVal</strong>,
y:<strong>byRef</strong>)</p>
<p>…</p>
<p>…</p>
<p>ENDPROCEDURE</p></td>
<td><p>Unless stated values passed to subroutines can be assumed to be
passed by value in the exam.</p>
<p>If this is relevant to the question <strong>byVal</strong> and
<strong>byRef</strong> will be used. In the case shown here x is passed
by value and y is passed by reference.</p></td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 41%" />
<col style="width: 45%" />
</colgroup>
<thead>
<tr class="header">
<th>Concept</th>
<th>Example Pseudocode</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td rowspan="2">Arrays / Lists</td>
<td><p>ARRAY names[5]</p>
<p>names[0] = "Ahmad"</p>
<p>names[1] = "Ben"</p>
<p>names[2] = "Catherine"</p>
<p>names[3] = "Dana"</p>
<p>names[4] = "Elijah"</p>
<p>PRINT(names[3])</p></td>
<td>Arrays should be 0 based and declared with the keyword array.</td>
</tr>
<tr class="even">
<td><p>ARRAY board[8,8]</p>
<p>board[0,0] = "rook"</p></td>
<td>Example of 2D array</td>
</tr>
<tr class="odd">
<td rowspan="4">Reading to and writing from files</td>
<td><p>myFile = <strong>OPENREAD</strong>("sample.txt")</p>
<p>x = myFile.<strong>READLINE</strong>()</p>
<p>myFile.<strong>CLOSE</strong>()</p></td>
<td><p>To open a file to read you should use OPENREAD.</p>
<p>READLINE should be used to return a line of text from the file.</p>
<p>The example on the left makes x the first line of sample.txt</p></td>
</tr>
<tr class="even">
<td>ENDOFFILE()</td>
<td>This is used to determine if the end of a file has been
reached.</td>
</tr>
<tr class="odd">
<td><p>myFile = OPENREAD("sample.txt")</p>
<p>WHILE NOT myFile.<strong>ENDOFFILE</strong>()</p>
<p>PRINT(myFile.READLINE())</p>
<p>ENDWHILE</p>
<p>myFile.CLOSE()</p></td>
<td>The example on the left will print out the contents of
sample.txt</td>
</tr>
<tr class="even">
<td><p>myFile = <strong>OPENWRITE</strong>("sample.txt")</p>
<p>myFile.<strong>WRITELINE</strong>("Hello World")</p>
<p>myFile.CLOSE()</p></td>
<td>To open a file to write to openWrite is used and writeLine to add a
line of text to the file. In the program below hello world is made the
contents of sample.txt (any previous contents are overwritten).</td>
</tr>
<tr class="odd">
<td>Comments</td>
<td>PRINT("Hello World") //This is a comment</td>
<td>Comments are denoted by //</td>
</tr>
</tbody>
</table>


<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 41%" />
<col style="width: 45%" />
</colgroup>
<thead>
<tr class="header">
<th>Concept</th>
<th>Example Pseudocode</th>
<th>Notes</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td rowspan="2">Methods and attributes</td>
<td><p>PUBLIC and PRIVATE</p>
<p>PRIVATE attempts = 3</p>
<p>PUBLIC PROCEDURE setAttempts(number)</p>
<p>attempts = number</p>
<p>ENDPROCEDURE</p>
<p>PRIVATE FUNCTION getAttempts()</p>
<p>RETURN attempts</p>
<p>END FUNCTION</p></td>
<td><p>Methods and attributes can be assumed to be public unless
otherwise stated.</p>
<p>Where the access level is relevant to the question it will always be
explicit in the code denoted by the keywords.</p></td>
</tr>
<tr class="even">
<td><p>player.setAttempts(5)</p>
<p>PRINT(player.getAttempts())</p></td>
<td>Methods should always be instance methods, you are not expected to
be aware of static methods. You should call them using object.method as
shown on the left.</td>
</tr>
<tr class="odd">
<td rowspan="4">Constructors and inheritance</td>
<td><p>CLASS Pet</p>
<p>PRIVATE name</p>
<p>PUBLIC PROCEDURE <strong>NEW</strong>(givenName)</p>
<p>Name = givenName</p>
<p>ENDPROCEDURE</p>
<p>ENDCLASS</p></td>
<td>You should write constructors as you would procedures with the name
new</td>
</tr>
<tr class="even">
<td>SUPER.methodName(parameters)</td>
<td><p>You should show Inheritance by using the keyword
<em>inherits</em> keyword</p>
<p><em>Superclass</em> methods should be called with the keyword
<em>super</em>.</p></td>
</tr>
<tr class="odd">
<td><p>CLASS dog <strong>INHERITS</strong> Pet</p>
<p>PRIVATE breed</p>
<p>PUBLIC PROCEDURE NEW(givenName, givenBreed)</p>
<p>SUPER.NEW(givenName)</p>
<p>Breed = givenBreed</p>
<p>ENDPROCEDURE</p>
<p>ENDCLASS</p></td>
<td>In the case of the constructor the pseudocode would look like the
example on the left.</td>
</tr>
<tr class="even">
<td><p>objectName = NEW className(parameters)</p>
<p>e.g.</p>
<p>myDog = NEW Dog("Fido","Scottish Terrier")</p></td>
<td>To create an instance of an object the following format is used</td>
</tr>
</tbody>
</table>

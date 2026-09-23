## Table of Contents

<details>
<summary><strong>Vocab</strong></summary>

<ul>
<li>
<details>
<summary><strong>Basics</strong></summary>
<ul>
<li><a href="#algorithm">algorithm</a></li>
<li><a href="#sequencing">sequencing</a></li>
<li><a href="#variable">variable</a></li>
<li><a href="#variable-declaration">variable declaration</a></li>
<li><a href="#variable-initialization">variable initialization</a></li>
<li><a href="#assignment">assignment</a></li>
<li><a href="#data-types">data types</a></li>
<li><a href="#string">String</a></li>
<li><a href="#int">int</a></li>
<li><a href="#double">double</a></li>
<li><a href="#boolean">boolean</a></li>
<li><a href="#console-output">console / output</a></li>
<li><a href="#concatenation">concatenation</a></li>
<li><a href="#type-conversion-casting">type conversion / casting</a></li>
</ul>
</details>
</li>

<li>
<details>
<summary><strong>Methods</strong></summary>
<ul>
<li><a href="#method">method</a></li>
<li><a href="#method-declaration">method declaration</a></li>
<li><a href="#method-call">method call</a></li>
<li><a href="#parameter">parameter</a></li>
<li><a href="#argument">argument</a></li>
<li><a href="#void">void</a></li>
<li><a href="#return-type">return type</a></li>
<li><a href="#return-statement">return statement</a></li>
<li><a href="#scope-local-variable">scope / local variable</a></li>
<li><a href="#method-overloading">method overloading</a></li>
</ul>
</details>
</li>

<li>
<details>
<summary><strong>User Input</strong></summary>
<ul>
<li><a href="#scanner">Scanner</a></li>
<li><a href="#user-input">user input</a></li>
<li><a href="#scanner-input-methods">Scanner input methods</a></li>
</ul>
</details>
</li>

<li>
<details>
<summary><strong>Operators</strong></summary>
<ul>
<li><a href="#arithmetic-operators">arithmetic operators</a></li>
<li><a href="#modulus">modulus (%)</a></li>
<li><a href="#increment-decrement">increment / decrement</a></li>
<li><a href="#compound-assignment">compound assignment</a></li>
<li><a href="#comparison-operators">comparison operators</a></li>
</ul>
</details>
</li>

<li>
<details>
<summary><strong>Control Structures</strong></summary>
<ul>
<li><a href="#conditional-statement">conditional statement</a></li>
<li><a href="#if-statement">if statement</a></li>
<li><a href="#if-else">if / else</a></li>
<li><a href="#if-else-if-else">if / else if / else</a></li>
<li><a href="#nested-if-statement">nested if statement</a></li>
<li><a href="#logical-operators">logical operators</a></li>
<li><a href="#compound-boolean-expression">compound boolean expression</a></li>
<li><a href="#de-morgans-law">De Morgan's Law</a></li>
<li><a href="#for-loop">for loop</a></li>
<li><a href="#while-loop">while loop</a></li>
<li><a href="#infinite-loop">infinite loop</a></li>
</ul>
</details>
</li>

<li>
<details>
<summary><strong>Classes and Objects</strong></summary>
<ul>
<li><a href="#class">class</a></li>
<li><a href="#object">object</a></li>
<li><a href="#instance">instance</a></li>
<li><a href="#instance-field">instance field</a></li>
<li><a href="#constructor">constructor</a></li>
<li><a href="#constructor-parameter">constructor parameter</a></li>
<li><a href="#new-keyword">new keyword</a></li>
<li><a href="#dot-notation">dot notation</a></li>
<li><a href="#static-vs-non-static-methods">static vs. non-static methods</a></li>
<li><a href="#abstraction">abstraction</a></li>
</ul>
</details>
</li>

<li>
<details>
<summary><strong>Useful Java Tools</strong></summary>
<ul>
<li><a href="#math-class">Math class</a></li>
<li><a href="#math-random">Math.random()</a></li>
</ul>
</details>
</li>
</ul>

</details>

<details>
<summary><strong>Code Examples</strong></summary>

<ul>
<li><a href="#starter-program-example">Starter Program Example</a></li>
<li><a href="#variables-and-updating-values-example">Variables and Updating Values Example</a></li>
<li><a href="#strings-and-concatenation-example">Strings and Concatenation Example</a></li>
<li><a href="#user-input-example">User Input Example</a></li>
<li><a href="#comparison-operators-example">Comparison Operators Example</a></li>
<li><a href="#if-statement-example">If Statement Example</a></li>
<li><a href="#if--else-example">If / Else Example</a></li>
<li><a href="#if--else-if--else-example">If / Else If / Else Example</a></li>
<li><a href="#compound-booleans-example">Compound Booleans Example</a></li>
<li><a href="#de-morgans-law-example">De Morgan's Law Example</a></li>
<li><a href="#for-loop-example">For Loop Example</a></li>
<li><a href="#while-loop-example">While Loop Example</a></li>
<li><a href="#arithmetic-and-modulus-example">Arithmetic and Modulus Example</a></li>
<li><a href="#method-with-parameters-example">Method with Parameters Example</a></li>
<li><a href="#method-that-returns-a-value-example">Method that Returns a Value Example</a></li>
<li><a href="#scope-example">Scope Example</a></li>
<li><a href="#method-overloading-example">Method Overloading Example</a></li>
<li><a href="#class-with-instance-fields-example">Class with Instance Fields Example</a></li>
<li><a href="#constructor-and-object-creation-example">Constructor and Object Creation Example</a></li>
<li><a href="#dot-notation-and-non-static-method-example">Dot Notation and Non-Static Method Example</a></li>
</ul>

</details>

<a href="#notebook-style-guide">Notebook Style Guide</a>

















## Vocab







### Basics

<details>
<summary id="algorithm">algorithm</summary>
<p><strong>Definition:</strong> A step-by-step process used to complete a task or solve a problem.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">int total = price1 + price2;
System.out.println(total);
</code></pre>
</details>

<details>
<summary id="sequencing">sequencing</summary>
<p><strong>Definition:</strong> The order in which instructions are completed. Changing the order can change the result.</p>
</details>

<details>
<summary id="variable">variable</summary>
<p><strong>Definition:</strong> A named storage location that holds a value that can change.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">int score = 10;
score = 15;
</code></pre>
</details>

<details>
<summary id="variable-declaration">variable declaration</summary>
<p><strong>Definition:</strong> Creating a variable by giving Java its data type and name.</p>
<p><strong>Structure / syntax:</strong></p>
<pre><code class="language-java">dataType variableName;
</code></pre>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">String weather;
</code></pre>
</details>

<details>
<summary id="variable-initialization">variable initialization</summary>
<p><strong>Definition:</strong> Giving a variable its first value when it is created.</p>
<p><strong>Structure / syntax:</strong></p>
<pre><code class="language-java">dataType variableName = value;
</code></pre>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">String weather = "sunny";
</code></pre>
</details>

<details>
<summary id="assignment">assignment</summary>
<p><strong>Definition:</strong> Using <code>=</code> to store or replace a value in a variable.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">weather = "rainy";
</code></pre>
</details>

<details>
<summary id="data-types">data types</summary>
<p><strong>Definition:</strong> Categories that tell Java what kind of value a variable can store.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">String name = "Alex";
int age = 16;
double height = 5.8;
boolean hasPermit = true;
</code></pre>
</details>

<details>
<summary id="string">String</summary>
<p><strong>Definition:</strong> A Java type used to store text.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">String playerName = "Alex";
</code></pre>
</details>

<details>
<summary id="int">int</summary>
<p><strong>Definition:</strong> A Java type used to store whole numbers.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">int lives = 3;
</code></pre>
</details>

<details>
<summary id="double">double</summary>
<p><strong>Definition:</strong> A Java type used to store numbers that may contain decimals.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">double price = 12.99;
</code></pre>
</details>

<details>
<summary id="boolean">boolean</summary>
<p><strong>Definition:</strong> A Java type that stores only <code>true</code> or <code>false</code>.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">boolean isLoggedIn = false;
</code></pre>
</details>

<details>
<summary id="console-output">console / output</summary>
<p><strong>Definition:</strong> The console displays information produced by a program. Information sent out by a program is output.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">System.out.println("Hello World!");
</code></pre>
</details>

<details>
<summary id="concatenation">concatenation</summary>
<p><strong>Definition:</strong> Combining Strings together with the <code>+</code> operator.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">String fullName = firstName + " " + lastName;
</code></pre>
</details>

<details>
<summary id="type-conversion-casting">type conversion / casting</summary>
<p><strong>Definition:</strong> Changing a value from one data type to another.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">int age = Integer.parseInt("16");
double price = 19.99;
int wholePrice = (int) price;
</code></pre>
<p>Casting a <code>double</code> to an <code>int</code> removes the decimal portion; it does not round.</p>
</details>











### Methods

<details>
<summary id="method">method</summary>
<p><strong>Definition:</strong> A reusable block of code that performs a task.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">static void sayHi() {
    System.out.println("Hi!");
}
</code></pre>
</details>

<details>
<summary id="method-declaration">method declaration</summary>
<p><strong>Definition:</strong> The code that defines a method's name, return type, parameters, and body.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">static void greet(String name) {
    System.out.println("Hello, " + name);
}
</code></pre>
</details>

<details>
<summary id="method-call">method call</summary>
<p><strong>Definition:</strong> An instruction that tells Java to run a method.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">greet("Jordan");
</code></pre>
</details>

<details>
<summary id="parameter">parameter</summary>
<p><strong>Definition:</strong> A variable listed in a method declaration that receives information.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">static void greet(String name) {
    System.out.println("Hello, " + name);
}
</code></pre>
</details>

<details>
<summary id="argument">argument</summary>
<p><strong>Definition:</strong> A value supplied to a method when it is called.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">greet("Jordan");
</code></pre>
</details>

<details>
<summary id="void">void</summary>
<p><strong>Definition:</strong> A method return type that means the method does not send a value back.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">static void printMessage() {
    System.out.println("Hello");
}
</code></pre>
</details>

<details>
<summary id="return-type">return type</summary>
<p><strong>Definition:</strong> The data type written before a method name that tells Java what type of value the method returns.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">static int getScore() {
    return 100;
}
</code></pre>
</details>

<details>
<summary id="return-statement">return statement</summary>
<p><strong>Definition:</strong> Sends a value back from a method and ends that method.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">static int add(int a, int b) {
    return a + b;
}
</code></pre>
</details>

<details>
<summary id="scope-local-variable">scope / local variable</summary>
<p><strong>Definition:</strong> Scope is where a name can be used. A local variable exists only inside the method or block where it is declared.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">static void example() {
    int score = 10;
    System.out.println(score);
}
// score cannot be used here
</code></pre>
</details>

<details>
<summary id="method-overloading">method overloading</summary>
<p><strong>Definition:</strong> Creating multiple methods with the same name but different parameter lists.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">static void show(int number) { }
static void show(String text) { }
</code></pre>
</details>

















### User Input

<details>
<summary id="scanner">Scanner</summary>
<p><strong>Definition:</strong> A Java class commonly used to read keyboard input.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">import java.util.Scanner;

Scanner input = new Scanner(System.in);
</code></pre>
</details>

<details>
<summary id="user-input">user input</summary>
<p><strong>Definition:</strong> Information entered into a program by the user while the program is running.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">System.out.print("Enter your age: ");
int age = input.nextInt();
</code></pre>
</details>

<details>
<summary id="scanner-input-methods">Scanner input methods</summary>
<p><strong>Definition:</strong> Methods used to read different kinds of input with a <code>Scanner</code>.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">String name = input.nextLine();
int age = input.nextInt();
double price = input.nextDouble();
</code></pre>
<p><code>nextLine()</code> reads text, <code>nextInt()</code> reads an integer, and <code>nextDouble()</code> reads a decimal number.</p>
</details>

















### Operators

<details>
<summary id="arithmetic-operators">arithmetic operators</summary>
<p><strong>Definition:</strong> Operators used for math: <code>+</code>, <code>-</code>, <code>*</code>, and <code>/</code>.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">int total = 5 + 2;
int product = 5 * 2;
double quotient = 5.0 / 2.0;
</code></pre>
</details>

<details>
<summary id="modulus">modulus (%)</summary>
<p><strong>Definition:</strong> Returns the remainder after division.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">System.out.println(10 % 3); // 1
</code></pre>
</details>

<details>
<summary id="increment-decrement">increment / decrement</summary>
<p><strong>Definition:</strong> <code>++</code> increases by 1. <code>--</code> decreases by 1.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">score++;
lives--;
</code></pre>
</details>

<details>
<summary id="compound-assignment">compound assignment</summary>
<p><strong>Definition:</strong> Combines an operation with assignment, such as <code>+=</code>, <code>-=</code>, <code>*=</code>, and <code>/=</code>.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">score += 5;
health -= 10;
</code></pre>
</details>

<details>
<summary id="comparison-operators">comparison operators</summary>
<p><strong>Definition:</strong> Compare two values and produce <code>true</code> or <code>false</code>: <code>==</code>, <code>!=</code>, <code>&lt;</code>, <code>&gt;</code>, <code>&lt;=</code>, <code>&gt;=</code>.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">System.out.println(score &gt;= 70);
System.out.println(lives != 0);
</code></pre>
</details>
















### Control Structures

<details>
<summary id="conditional-statement">conditional statement</summary>
<p><strong>Definition:</strong> A statement that makes a decision based on a boolean condition.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">if (temperature &lt; 50) {
    System.out.println("Wear a jacket.");
}
</code></pre>
</details>

<details>
<summary id="if-statement">if statement</summary>
<p><strong>Definition:</strong> Runs a block of code only when its condition is true.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">if (score &gt;= 90) {
    System.out.println("A");
}
</code></pre>
</details>

<details>
<summary id="if-else">if / else</summary>
<p><strong>Definition:</strong> Chooses between two paths.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">if (age &gt;= 18) {
    System.out.println("Adult");
} else {
    System.out.println("Minor");
}
</code></pre>
</details>

<details>
<summary id="if-else-if-else">if / else if / else</summary>
<p><strong>Definition:</strong> Checks multiple conditions in order and runs the first matching branch.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">if (score &gt;= 90) {
    System.out.println("A");
} else if (score &gt;= 80) {
    System.out.println("B");
} else {
    System.out.println("Below B");
}
</code></pre>
</details>

<details>
<summary id="nested-if-statement">nested if statement</summary>
<p><strong>Definition:</strong> An <code>if</code> statement placed inside another conditional statement.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">if (age &gt;= 16) {
    if (hasPermit) {
        System.out.println("Can practice driving");
    }
}
</code></pre>
</details>

<details>
<summary id="logical-operators">logical operators</summary>
<p><strong>Definition:</strong> Operators used with booleans: <code>&amp;&amp;</code> means AND, <code>||</code> means OR, and <code>!</code> means NOT.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">boolean canDrive = age &gt;= 16 &amp;&amp; hasPermit;
boolean canEnter = hasID || hasPass;
boolean unlocked = !isLocked;
</code></pre>
</details>

<details>
<summary id="compound-boolean-expression">compound boolean expression</summary>
<p><strong>Definition:</strong> A boolean expression made by combining two or more conditions.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">boolean eligible = age &gt;= 16 &amp;&amp; hasPermit;
</code></pre>
</details>

<details>
<summary id="de-morgans-law">De Morgan's Law</summary>
<p><strong>Definition:</strong> Rules for rewriting negated compound boolean expressions.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">!(A &amp;&amp; B)  // same as !A || !B
!(A || B)  // same as !A &amp;&amp; !B
</code></pre>
</details>

<details>
<summary id="for-loop">for loop</summary>
<p><strong>Definition:</strong> A loop commonly used when initialization, condition, and update can be written together.</p>
<p><strong>Structure / syntax:</strong></p>
<pre><code class="language-java">for (initialization; condition; update) {
    // repeated code
}
</code></pre>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">for (int i = 0; i &lt; 5; i++) {
    System.out.println(i);
}
</code></pre>
</details>

<details>
<summary id="while-loop">while loop</summary>
<p><strong>Definition:</strong> A loop that repeats while its condition remains true.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">int count = 0;
while (count &lt; 5) {
    System.out.println(count);
    count++;
}
</code></pre>
</details>

<details>
<summary id="infinite-loop">infinite loop</summary>
<p><strong>Definition:</strong> A loop that never stops because its condition never becomes false.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">int count = 0;
while (count &lt; 5) {
    System.out.println(count);
    // count never changes
}
</code></pre>
</details>
















### Classes and Objects

<details>
<summary id="class">class</summary>
<p><strong>Definition:</strong> A blueprint that describes the data and behaviors objects of that type can have.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">public class Friend {

}
</code></pre>
</details>

<details>
<summary id="object">object</summary>
<p><strong>Definition:</strong> A specific object created from a class.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">Friend jasmine = new Friend("Jasmine", 15);
</code></pre>
</details>

<details>
<summary id="instance">instance</summary>
<p><strong>Definition:</strong> Another name for an object created from a class.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">Friend jasmine = new Friend("Jasmine", 15);
</code></pre>
</details>

<details>
<summary id="instance-field">instance field</summary>
<p><strong>Definition:</strong> A variable declared in a class that stores information for each object.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">public class Friend {
    String name;
    int age;
}
</code></pre>
</details>

<details>
<summary id="constructor">constructor</summary>
<p><strong>Definition:</strong> A special part of a class that runs when a new object is created and usually gives it starting values.</p>
<p><strong>Structure / syntax:</strong></p>
<pre><code class="language-java">public ClassName(parameters) {
    // setup code
}
</code></pre>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">public Friend(String friendName, int friendAge) {
    name = friendName;
    age = friendAge;
}
</code></pre>
</details>

<details>
<summary id="constructor-parameter">constructor parameter</summary>
<p><strong>Definition:</strong> A parameter in a constructor that receives a value when a new object is created.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">public Friend(String friendName, int friendAge) {
    name = friendName;
    age = friendAge;
}
</code></pre>
</details>

<details>
<summary id="new-keyword">new keyword</summary>
<p><strong>Definition:</strong> The keyword used to create a new object from a class.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">Friend jasmine = new Friend("Jasmine", 15);
</code></pre>
</details>

<details>
<summary id="dot-notation">dot notation</summary>
<p><strong>Definition:</strong> Using a dot after an object name to access one of its fields or methods.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">System.out.println(jasmine.name);
jasmine.greeting();
</code></pre>
</details>

<details>
<summary id="static-vs-non-static-methods">static vs. non-static methods</summary>
<p><strong>Definition:</strong> A static method belongs to the class. A non-static method belongs to an object and can directly use that object's instance fields.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">static void classMessage() {
    System.out.println("Class method");
}

void greeting() {
    System.out.println("Hello, " + name);
}
</code></pre>
</details>

<details>
<summary id="abstraction">abstraction</summary>
<p><strong>Definition:</strong> Using a simpler name or interface without handling all internal details every time.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">Friend jasmine = new Friend("Jasmine", 15);
System.out.println(jasmine.name);
</code></pre>
</details>
















### Useful Java Tools

<details>
<summary id="math-class">Math class</summary>
<p><strong>Definition:</strong> A built-in Java class containing useful static math methods and constants.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">double root = Math.sqrt(25);
double power = Math.pow(2, 3);
double absolute = Math.abs(-7);
</code></pre>
</details>

<details>
<summary id="math-random">Math.random()</summary>
<p><strong>Definition:</strong> Returns a random <code>double</code> from 0.0 up to, but not including, 1.0.</p>
<p><strong>Java example:</strong></p>
<pre><code class="language-java">int randomNumber = (int) (Math.random() * 10) + 1;
</code></pre>
<p>This example creates a random integer from 1 through 10.</p>
</details>



















## Code Examples

### Starter Program Example

```java
public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

### Variables and Updating Values Example

```java
int score = 10;
score = 15;
System.out.println(score);
```

### Strings and Concatenation Example

```java
String firstName = "Dev";
String lastName = "Cat";
System.out.println(firstName + " " + lastName);
```

### User Input Example

```java
import java.util.Scanner;

Scanner input = new Scanner(System.in);
System.out.print("Enter your name: ");
String name = input.nextLine();
```

### Comparison Operators Example

```java
int score = 85;
System.out.println(score == 85);
System.out.println(score != 100);
System.out.println(score >= 70);
```

### If Statement Example

```java
if (score >= 90) {
    System.out.println("A");
}
```

### If / Else Example

```java
if (age >= 18) {
    System.out.println("Adult");
} else {
    System.out.println("Minor");
}
```

### If / Else If / Else Example

```java
if (score >= 90) {
    System.out.println("A");
} else if (score >= 80) {
    System.out.println("B");
} else {
    System.out.println("Below B");
}
```

### Compound Booleans Example

```java
boolean canDrive = age >= 16 && hasPermit;
boolean canEnter = hasID || hasPass;
boolean lockedOut = !hasAccess;
```

### De Morgan's Law Example

```java
!(A && B)   // same as !A || !B
!(A || B)   // same as !A && !B
```

### For Loop Example

```java
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}
```

### While Loop Example

```java
int count = 0;
while (count < 5) {
    System.out.println(count);
    count++;
}
```

### Arithmetic and Modulus Example

```java
int total = 7 + 3;
int product = 7 * 3;
int remainder = 10 % 3;
```

### Method with Parameters Example

```java
static void greet(String name) {
    System.out.println("Hello, " + name);
}

greet("Jordan");
```

### Method that Returns a Value Example

```java
static int add(int a, int b) {
    return a + b;
}

int total = add(4, 6);
```

### Scope Example

```java
static void example() {
    int score = 10;
}
// score cannot be used here
```

### Method Overloading Example

```java
static void show(int number) { }
static void show(String text) { }
```

### Class with Instance Fields Example

```java
public class Friend {
    String name;
    int age;
}
```

### Constructor and Object Creation Example

```java
public class Friend {
    String name;
    int age;

    public Friend(String friendName, int friendAge) {
        name = friendName;
        age = friendAge;
    }

    public static void main(String[] args) {
        Friend jasmine = new Friend("Jasmine", 15);
    }
}
```

### Dot Notation and Non-Static Method Example

```java
public void greeting() {
    System.out.println("Hello, " + name);
}

Friend jasmine = new Friend("Jasmine", 15);
System.out.println(jasmine.name);
jasmine.greeting();
```


















































## Notebook Style Guide

Keep your notebook useful for **you**. Add examples, corrections, and notes as you learn.

- Use `##` for major sections.
- Use `###` for categories and examples.
- Use **bold** for important ideas.
- Use `inline code` for short Java syntax.
- Use fenced Java code blocks for multi-line examples:

````markdown
```java
System.out.println("Hello World!");
```
````

- Add comments when they explain **why** something is happening.
- Keep examples small enough that you can quickly understand them later.
- When you make a mistake, add the corrected example if it will help you avoid the same mistake again.

### Bottom Line

**Definitions tell you what something means. Code examples show you how to use it. Your notebook should have both.**
`````

System Output

::sout::

Output: System.out.println("");

::souf::

Output: System.out.printf("");
Loops and Conditionals

::fori::

Output:
java
Copy code
for (int i = 0; i < ; i++) {
}

::ifs::

Output:
java
Copy code
if() {
} else if() {
} else {
}

::if::

Output:
java
Copy code
if() {
}

::else::

Output:
java
Copy code
else {
}

::while::

Output:
java
Copy code
while(true) {
}

Main Method and Class

::psvm::

Output:
java
Copy code
public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
}

::pc::

Output:
java
Copy code
import java.util.*;
public class {
}

Scanner Inputs

::sci::

Output: = sc.nextInt();

::scd::

Output: = sc.nextDouble();

::scs::

Output: = sc.nextLine();

::scb::

Output: = sc.nextBoolean();

::scc::

Output: = sc.next().charAt(0);

Property Definitions

::props::

Output:
java
Copy code
private String stringProperty;
public String getStringProperty() {
    return stringProperty;
}
public void setStringProperty(String stringProperty) {
    this.stringProperty = stringProperty;
}
::propb::

Output:
java
Copy code
private boolean booleanProperty;
public boolean getBooleanProperty() {
    return booleanProperty;
}
public void setBooleanProperty(boolean booleanProperty) {
    this.booleanProperty = booleanProperty;
}

::propd::

Output:
java
Copy code
private double doubleProperty;
public double getDoubleProperty() {
    return doubleProperty;
}
public void setDoubleProperty(double doubleProperty) {
    this.doubleProperty = doubleProperty;
}

::propi::

Output:
java
Copy code
private int intProperty;
public int getIntProperty() {
    return intProperty;
}
public void setIntProperty(int intProperty) {
    this.intProperty = intProperty;
}

::propc::

Output:
java
Copy code
private char charProperty;
public char getCharProperty() {
    return charProperty;
}
public void setCharProperty(char charProperty) {
    this.charProperty = charProperty;
}
Method Definitions

::funcs::

Output:
java
Copy code
public String functionName() {
    return ;
}

::funcv::

Output:
java
Copy code
public void functionName() {
    
}

::funci::

Output:
java
Copy code
public int functionName() {
    return ;
}

::funcd::

Output:
java
Copy code
public double functionName() {
    return ;
}

::funcb::

Output:
java
Copy code
public boolean functionName() {
    return ;
}
Public Property Definitions

::pub::

Output:
java
Copy code
public boolean booleanProperty;

::pus::

Output:
java
Copy code
public String stringProperty;

::pui::

Output:
java
Copy code
public int intProperty;

::pud::

Output:
java
Copy code
public double doubleProperty;

::puc::

Output:
java
Copy code
public char charProperty;

::tostring::

Output:
java
Copy code
@Override
public String toString() {
    return "ClassName{" 
        + "stringProperty='" + stringProperty + "'" 
        + ", booleanProperty=" + booleanProperty 
        + ", doubleProperty=" + doubleProperty 
        + ", intProperty=" + intProperty 
        + '}';
}

::cons::

Output:
java
Copy code
public ClassName(int intProperty, char charProperty, String stringProperty, double doubleProperty) {
    this.intProperty = intProperty;
    this.charProperty = charProperty;
    this.stringProperty = stringProperty;
    this.doubleProperty = doubleProperty;
}

::con::

Output:
java
Copy code
public ClassName(int intProperty) {
    this.intProperty = intProperty;
}

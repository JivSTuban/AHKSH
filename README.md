System Output

::sout::

Output: System.out.println("");

::souf::

Output: System.out.printf("");
Loops and Conditionals

::fori::

Output:

for (int i = 0; i < ; i++) {
}

::ifs::

Output:

if() {
} else if() {
} else {
}

::if::

Output:


if() {
}

::else::

Output:

else {
}

::while::

Output:

while(true) {
}

Main Method and Class

::psvm::

Output:

public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
}

::pc::

Output:

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

private String stringProperty;
public String getStringProperty() {
    return stringProperty;
}
public void setStringProperty(String stringProperty) {
    this.stringProperty = stringProperty;
}
::propb::

Output:

private boolean booleanProperty;
public boolean getBooleanProperty() {
    return booleanProperty;
}
public void setBooleanProperty(boolean booleanProperty) {
    this.booleanProperty = booleanProperty;
}

::propd::

Output:

private double doubleProperty;
public double getDoubleProperty() {
    return doubleProperty;
}
public void setDoubleProperty(double doubleProperty) {
    this.doubleProperty = doubleProperty;
}

::propi::

Output:

private int intProperty;
public int getIntProperty() {
    return intProperty;
}
public void setIntProperty(int intProperty) {
    this.intProperty = intProperty;
}

::propc::

Output:

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

public String functionName() {
    return ;
}

::funcv::

Output:

public void functionName() {
    
}

::funci::

Output:

public int functionName() {
    return ;
}

::funcd::

Output:

public double functionName() {
    return ;
}

::funcb::

Output:

public boolean functionName() {
    return ;
}
Public Property Definitions

::pub::

Output:

public boolean booleanProperty;

::pus::

Output:

public String stringProperty;

::pui::

Output:

public int intProperty;

::pud::

Output:

public double doubleProperty;

::puc::

Output:

public char charProperty;

::tostring::

Output:

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

public ClassName(int intProperty, char charProperty, String stringProperty, double doubleProperty) {
    this.intProperty = intProperty;
    this.charProperty = charProperty;
    this.stringProperty = stringProperty;
    this.doubleProperty = doubleProperty;
}

::con::

Output:

public ClassName(int intProperty) {
    this.intProperty = intProperty;
}

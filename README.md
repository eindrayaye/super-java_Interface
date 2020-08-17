# super-java_Interface

-Another way to achieve abstraction in Java is the Interface.
-An interface is a completely "Abstract class" that is used to group related methods with empth bodies.
-To access the interface method, the interface must be "Implemented" by another class with the implements keyword (Instead of extends)
-The body of the unterface method is provided by the implement class.

(Example: how to write Interface method)

interface Animal {

  public void animalSound; // Empty Body
  
  public void sleep;       //
  
  }
*******************

In example three .java files

(1) AccountInfo.java (Parent class) has 'content' and 'banknam' Methods.

(2) CurrentAccount.java & SavingAccount.java are child classes that using 'implements' keyword instad of 'extends'.

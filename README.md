# DesignPattern
Design patterns learning sample

Design Patterns grouped into 3 based on its characteristics, namely :
1. Structural (S)
2. Behavioral (B)
3. Creational (C)

Wise words :
#1 Design Pattern doesn't go directly into your code, they first go into your BRAIN
#2 Knowing A.P.I.E. doesn't make you a good OO designer


#1 Strategy Pattern (B)
Key Points :
1. Take what varies and separate them from what stays the same
2. Program to an Interface(as general), not an Implementation
3. Favor Composition over Inheritance

#2 Observer Pattern (B)
Key Points :
1. Publisher + Subscriber/Observer
2. One-To-Many relationship, ONE Publisher MANY Subscriber/Observer
3. Loosely coupling, Publisher don't care about concrete Subscriber/Observer, it will always notify any object that implements Subscriber/Observer interface
4. Holywood Principle, Don't call us, we call you

#3 Decorator Pattern (S)
Key Points :
1. Extention at runtime, rather than compile time
2. O/C Principle, Class should be open for extension, but closed for modification
3. Object Wrapper
4. Using Inheritance to match Type, not to get Behaviour
5. Don't rely on concrete component's type
6. Component + Decorator

#4 Factory Pattern (C)
Key Points :
1. Encapsulating object creation
2. 
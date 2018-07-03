# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
    Many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
    An object can have the form of its own class and that of its class's superclass (it can pass multiple "is a" tests).
    For example, Edward can have the forms Student and Person (Edward is a Student; Edward is a Person).

3. What can we use to implement polymorphism in Java?
    Inheritance: "[sub]class extends [super]class".

4. How many 'forms' can an object take when using polymorphism?
    Many.

5. Give an example of when you could use polymorphism.
    When modelling animal taxonomy: a rat is a rodent is a mammal is an animal is a living thing.


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
    Composition is a "has a" relationship. A class has an instance of another class as one of its attributes.

7. When would you use composition? Provide a simple example in Java.
    A car has an engine. A sports team has a bus.

8. What is/are the advantage(s) of using composition?
    Vs inheritance, composition allows use of data/form from many classes rather than only one.
    Composition is more flexible: it can be changed during run-time.
    Composition maintains encapsulations, which may be broken by inheritance.

9. What happens to the behaviours when the object composed of them is destroyed?
    They will be destroyed also.

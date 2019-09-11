# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
Many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
The ability of an object to take on many forms. Normally when a parent class passess its characteristics to a child object.

3. What can we use to implement polymorphism in Java?
We can use interfaces or abstract classes in Java to implement polymorphism. Using abstract classes, the parameters are passed down as a superclass.

4. How many 'forms' can an object take when using polymorphism?
One abstract class or unlimited interfaces


5. Give an example of when you could use polymorphism.
A zoo could have a list of animals. The animal class could be an abstract class which passes down characteristics to indivdual animals. 


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
Composition ensure that dependencies are abstract instead on concrete.

7. When would you use composition? Provide a simple example in Java.
In the zoo example above the individual animals could take an interface to allow them to be grouped into a single zoo arrayList holding all the owned animals.

8. What is/are the advantage(s) of using composition?
Allows simpler addition of modification of associated classes.

9. When an object is destroyed, what happens to all the objects it is composed of? All the 'owned' objects are also destroyed. 

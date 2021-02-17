# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
The ability of an object to take many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
An object can have more than one type. A vegetable object can be a vegetable and a food object as well.

3. What can we use to implement polymorphism in Java?
We either use inheritance or we implement interfaces.

4. How many 'forms' can an object take when using polymorphism?
I think as many as we want?

5. Give an example of when you could use polymorphism.
When a superclass say Vehicle has a function that would be passed to all it's children, for example Car will have the method "turnLeft()


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
That an object is part of another object.

7. When would you use composition? Provide a simple example in Java.
An example from yesterday's lab, when we created a Car class which contained other objects like a Wheels, Engine and Doors class.

8. Give a difference between composition and aggregation?
Both use objects and behaviors of these objects, but aggregation makes it possible to them to exist independently.

9. What is/are the advantage(s) of using composition/aggregation?
We can use other object's behaviors whenever we need, without worrying about inheritance. Also, using aggregation we can compose a class using other objects, and if later we decide to delete this class, these objects will remain.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
The objects will be destroyed.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
The objects remain untouched.
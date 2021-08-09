# Stack

Java Collection framework provides a Stack class that models and implements a Stack data structure. 
The class is based on the basic principle of last-in-first-out. In addition to the basic push and pop operations, the class provides three more functions of empty, search, and peek. 
The class can also be said to extend Vector and treats the class as a stack with the five mentioned functions. 
The class can also be referred to as the subclass of Vector. 

The class supports one default constructor Stack() which is used to create an empty stack. 

# Declaration:

public class Stack<E> extends Vector<E>

# All Implemented Interfaces:

1. Serializable: It is a marker interface that classes must implement if they are to be serialized and deserialized.

2. Cloneable: This is an interface in Java which needs to be implemented by a class to allow its objects to be cloned.

3. Iterable<E>: This interface represents a collection of objects which is iterable — meaning which can be iterated.

4. Collection<E>: A Collection represents a group of objects known as its elements. The Collection interface is used to pass around collections of objects where maximum generality is desired.

5. List<E>: The List interface provides a way to store the ordered collection. It is a child interface of Collection.

6. RandomAccess: This is a marker interface used by List implementations to indicate that they support fast (generally constant time) random access.


# How to create a stack:

In order to create a stack, we must import java.util.stack package and use the Stack() constructor of this class. The below example creates an empty Stack.

Stack<E> stack = new Stack<E>();

Here E is the type of Object.

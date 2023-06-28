# Polymorphism

What does the word 'polymorphism' mean?
	
 Polymorphism means multiple morphs. It calls something that can change morphs( images), so it can be fit in different situations.   
 
What does it mean when we apply polymorphism to OO design? Give a simple Java example.

	In OO design it means that classes can be manipulated in a way that different classes-objects can be uniformed based on common sets of methods or operations. A person can be a student, a teacher,  a secretary or a cleaner in a school because they share common fields like name, age, genre, etc
 
What can we use to implement polymorphism in Java?

	In java we use inheritance and interfaces.
 
How many 'forms' can an object take when using polymorphism?

	There is no limit on that.
 
Give an example of when you could use polymorphism.

	 A person can be a student, a teacher,  a secretary or a cleaner in a school because they share common fields like name, age, genre, etc
  
What do we mean by 'composition' in reference to object-oriented programming?

	Composition refers to a “has-a” relationship of objects. Different objects are being composed to create one more complex object.
 
When would you use composition? Provide a simple example in Java.

	When complex object need  simple objects to be created like the example
```
class Book{
   public void openBook(){
       System.out.println("The book is opened!");
   }
}
class Student{
   private Book book;
  
   public Student(Book book){
       this.book = book;
   }
  
   public  void canReadFromBook(){
       book.openBook();
       System.out.println("I am reading from book");
   }
}
```

Give a difference between composition and aggregation?


What is/are the advantage(s) of using composition/aggregation?
When using composition, when an object is destroyed, what happens to all the objects it is composed of?
When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?


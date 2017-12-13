# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

  The ability to take many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

  Applying polymorphism to OO design means that subclasses inherit from interfaces. this allows generic methods to be housed in those
  interfaces making it easier to call them across the project.

  public interface IConnect {

    public String connect(String data);


3. What can we use to implement polymorphism in Java?

  interfaces (abstracts?)

4. How many 'forms' can an object take when using polymorphism?

  unlimited??

5. Give an example of when you could use polymorphism.
dog and cat extending animal



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

  composition is having an instance of another class. another use of inheritence.

7. When would you use composition? Provide a simple example in Java.

@Test
    public void canSetOutputDevice(){
        Printer printer = new Printer("epson", "stylus", 120, 4);
        computer.setOutputDevice(printer);
        assertEquals("printing: space invaders", computer.outputData("space invaders"));

8. What is/are the advantage(s) of using composition?

  very flexible

9. What happens to the behaviours when the object composed of them is destroyed?

  

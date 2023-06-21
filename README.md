# Experiment-7

# Inheritance

## Aim:
  To write a Java program using inheritance one class can acquire the properties of others.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class called "Animal" and create required statements.

Step 3 : Create a another class called "Bird" and create required statements.

Step 3 : Create another class,called the Solution Class.

Step 4 : Using the 'extends' keyword you can inherit classes, do the same with above created class.

Step 5 : Display the statements from the first and second Class using Solution Class in the terminal.

## Program

```
class Animal{
void walk(){
System.out.println("I am walking");
  }
}

class Bird extends Animal{
void fly(){
System.out.println("I am flying");
  }
}

public class Solution{
public static void main(String args[]){
Bird bird = new Bird();
bird.walk();
bird.fly();
  }
}
```

## Output
![5](https://github.com/SaiDarshan2003/Experiment-5/assets/94692595/4f5aac52-cd72-4c09-b8e4-5c497980eabe)

## Result 
  We have successfully created a Java program using inheritance one class can acquire the properties of others.

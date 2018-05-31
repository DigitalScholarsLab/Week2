# Conditionals and Control Flow 
## Boolean Operators (AND, OR, NOT)
```
public class Boolean{
  public static void main(String[] args){
    System.out.println();
    System.out.println(false);
    System.out.println(5>=1);
  }
}
```
1. Use the && operator and any two Boolean expressions of your choice between the parentheses of System.out.println(); in 
order to print out a value of true or false to the console.
2. Use the ! operator to return a value of true for the code on line 4.
3. Use the ! operator to return a value of false for the code on line 5.

## Precedence (() ! && ||)

```
boolean riddle = /**/( 1 < 8 /**/ (5 > 2 /**/ 3 < 5));
System.out.println(riddle);

```
1. The code statement is incomplete. Use each Boolean operator no more than once to replace the empty comments /**/.
The code statement should print out false.

## If - Statements 

1. The if statement is missing its Boolean expression. Copy and paste to editor and provide a if statement 
that evaluates to true.
```
if () {
  System.out.println(access granted); 
}
```
2.	The code currently prints the if, Modify the if so it prints the else 
```
if (7 <= 7) {
  System.out.println("Try again...");
} 
else {
  System.out.println("Success!");
}
```
1.	Set the value of the round variable so the else if runs.
```
public class IfElseIf {
  public static void main(String[] args) {
    int round;
    if (round > 12) {
      System.out.println("The match is over!");
    } 
    else if (round > 0) {
      System.out.println("The match is underway!");
    }	
    else {
      System.out.println("The boxing match hasn't started yet.");
    }	
	}
}

```
## Project 2 Continents and Cities
Let's practice using if statements!
In this project, you will write a program that will print out a continent and the largest city in that continent, 
based on the value of an integer. Copy code to IDE to begin.
```
public class LargestCity {
  public static void main(String[]args){

  }
}
```

1. Create an int variable called continent and set it equal to 4.

2. Create if, else - if - statements with a boolean expression that checks if continent is equal to 1-7. 

3. When the value of continent is 1, print out North America: Mexico City, Mexico.

4. When the value of continent is 2, print out South America: Sao Paulo, Brazil.

5. When the value of continent is 3, print out Europe: Moscow, Russia. 

6. When the value of continent is 4, print out Africa: Lagos, Nigeria.
 
7. When the value of continent is 5, print out Asia: Shanghai, China. 

8. When the value of continent is 6, print out Australia: Sydney, Australia. 

9. When the value of continent is 7, print out Antarctica: McMurdo Station, US. 

10. Finally, add a default case "else", The default case should print out Undefined continent! 

 If the program is written correctly, your output should be Africa: Lagos, Nigeria.

 Add comments near the top of the program that describe what the program does.


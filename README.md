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
## Project #2: Episodes
Your Episode will allow the user to become a character in your story. Fill your story with love, romance, adventure, and drama. Start by copying and pasting the below code fragment into the online compiler. From here the details are up to you. Use your print statements, if statements, and nested if statements to create a story.




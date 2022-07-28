# Compsci 235 Lance Nillo Lab 1 Report

## Notes

### Software Versioning

- Purpose is to ensure disk space is not wasted.
- First digit: A major release that is **incompantible with previous version**
- Second digit: A minor release that **adds additional features** and guarantees backward compatibility
- Third digit: A **patch** for bug fixes; This should never break backward compatibility.

### Virtual Environment

- A virtual isolation of Python version and installed packages
- Allows user to run old projects regardless of new package updates.

### Debugging

- **Breakpoint**: Halts execution of program
- **Step into**, **Step over**, **Step into**: Traverses through code

## Reflection

Through this lab I have become more familiar with git/github. I am writing this report on my github and learning about markdowns also. I also refamiliarised myself with debugging and how to use it in a project. The notes I have included reflect what I did not know before the lab, specifically the intricacies of Software Versioning, Virtual Environment and Debugging.

## Solution for Exercise

***Question 1:     What is the probability of winning a game?***

1/100
    
***Question 2:     Using the debugging feature, WITHOUT changing any code, it is possible to win every game. What line did you insert the breakpoint at?*** 

34 

This is because this line is just before the program selects the computers program with the pickANumber() function. Adding the breakpoint to line 34 allows me to step over and see the number that computer_pick_number function will return (and is the selected computer number). Using this knowledge I can just read and input this number when prompted to guess. 

***Question 3:     Using the debugging feature only, is it possible the user can win every game by guessing "42"?*** 
    
No 

This is because the debugging feature does not affect my ability to make the computer generate 42. It only allows me to see what number it generates then guess accordingly. There is still a 1/100 chance of the computer picking 42.


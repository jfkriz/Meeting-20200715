# Meeting-20200715

## Exercise: Validate Parentheses

Write a function, Valid Parentheses, that takes a string of parentheses, and determines if the order of the parentheses is valid.This function should return true if the string is valid, and false if it's invalid.        
Specification
        	valid_parentheses(braces)
        	// Checks if the parentheses order is valid

Parameters
	braces: string - A string representation of an order of parentheses	// assume input string contains only open and/or closed parentheses
Return Value
        	bool - Returns true if order of parentheses are valid, false otherwise
Examples:
        	Input 		Output
        	"()“		true
        	 ")(()))“		false
        	 "(“		false
        	 "(())((()())())“	true 

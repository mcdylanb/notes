## Flow Control Statements  
<details>
<summary>What do you mean of Flow Control Statements?</summary>

- can decide which python instructions to execute under which conditions
</details>


## Boolean Values
<details>
<summary>What are the only two values does Boolean have?</summary> 

- truee
- false
</details>	

- basic kind of programming instruction in the language
- are just values combined with operators
- always evaluate down to a single value

### Comparison Operators

 Operator | Meaning
 --- | ---
 == | Equal to
 != | Not equal to 
 < | Less than
 <= | Less than or eual to 

> The DIfference Betwen The == and = Operators  
> - The == orator asks whether two values are the same as each other  
> - the = operator puts the value on the right into the variable on the left 

## Boolean Operators
<details>
	<summary> What are the three Boolean Operators?</summary>

1. and
2. or
3. not
	
</details>

## Elements of Flow Control
<details>
<summary>What are the Elements of Flow Control</summary>
	
- conditions
	- evaluate down to a boolean value 
- Blocks of code
	- Blocks 
		- grouped of code
</details>
<details>
<summary>What are the three rules of Blocks</summary>

1. Blocks begin when the indention increases
2. blocks can conatin other blocks
3. Blocks end when the indention decreases
</details>

### Program Execution
</details>
<details>
<summary>What is Program Execution(execution)?</summary>

- term for the current instructions being executed
</details>


## FLow Control Statements
- If statements
	- statements clause will execute if the statements condition is True
	- Skipped if the condition is False
	- Consist of:
		- the if Keyword
		- A condition
		- A colon
		- an indented block of code

- Else Statements
	- executed only when the if statements condition is False
	- Consist of:
		- the  Else keyword
		- colon
		- block of code

- Elif Statements
	- else if
	- allows follows an if or another elif statement
	- provides another condition
		- if only the previous condition was False
	- Consist of:
		- the Elif keyword
		- a condition
		- colon
		- indented block of code

- While Loop
	- th ecodition is always checked at the start of each *iteration*
	- iteration - each time loop is executed

>## Statements used inside loops
>- break statements
>	- if the execution reaches a break statement, immediatley exits the while loop.
>
>- Continue Statements
>	- when program execution reaches a continue statement, the program execution immediately jumps back to the start of the loop
>- sys.exit()

> ## Note
>- 0, 0.0, '' = false
>- any other valie = true

- for loops
	- include the following:
		- the for keyword
		- variable name
		- in keyword
		- call to the range() method
		- colon
		- indented block of code
	- ex:
```
		print('My name is ')
		for i in range(5):
			print('Jimmy Five times (' +str(i) + ')')
```
- Range()
	- Three arguements
		- Start
		- Stop
		- Step Arguement

## Importing Modules
- Built In Functions
	- Basic Functions
- Standard Library
	- Python comes with this library
- each module is a Python program that contains related group of functions that can be embedded in your programs
- before you can use, you need to import:
	- The import Keyword
	- the name of the module
	- Optionaly, more module names, seperated with comas

	> Notes
	> Dont Overwrite Module Names

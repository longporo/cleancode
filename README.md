# Clean Code
Clean = Readable + Understanding
<br>

# Naming

## Common prefix

- is

- can

- has/icludes/contains

- should/needs

## Create/Destroy

 <table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Create</td>
			<td>Create an instance, used in instantiated and factory methods</td>
		</tr>
		<tr>
			<td>Initialize</td>
			<td>Initializes the properties and settings for the instance</td>
		</tr>
		<tr>
			<td>Uninitialize</td>
			<td>Clean up the properties and Settings of the instance, as&nbsp;opposed&nbsp;to Initialize</td>
		</tr>
		<tr>
			<td>Load</td>
			<td>Load content from the configuration</td>
		</tr>
		<tr>
			<td>Destroy</td>
			<td>Destroy instance</td>
		</tr>
	</tbody>
</table>

## Get/Set
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Get</td>
			<td>Get properties,&nbsp;things you can get directly</td>
		</tr>
		<tr>
			<td>Fetch</td>
			<td>Data from network</td>
		</tr>
		<tr>
			<td>Calculate</td>
			<td>Data need to be calculated</td>
		</tr>
		<tr>
			<td>Read</td>
			<td>Data from files or configurations</td>
		</tr>
		<tr>
			<td>Query</td>
			<td>Data from DB</td>
		</tr>
		<tr>
			<td>Find</td>
			<td>Data from DB or list container</td>
		</tr>
		<tr>
			<td>Receive</td>
			<td>Receive files or messages</td>
		</tr>
		<tr>
			<td>Pull</td>
			<td>Pull</td>
		</tr>
		<tr>
			<td>Set</td>
			<td>Set properties</td>
		</tr>
		<tr>
			<td>Write</td>
			<td>Write into files or configuration</td>
		</tr>
		<tr>
			<td>Put</td>
			<td>Put in</td>
		</tr>
		<tr>
			<td>Push</td>
			<td>Save in, push messages</td>
		</tr>
	</tbody>
</table>

## Update

<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Reset</td>
			<td>Reset sign or status</td>
		</tr>
		<tr>
			<td>Refresh</td>
			<td>Refresh page or cache</td>
		</tr>
		<tr>
			<td>Update</td>
			<td>Update configuration or status</td>
		</tr>
	</tbody>
</table>

## Add/Remove
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Add</td>
			<td>Add things</td>
		</tr>
		<tr>
			<td>Append</td>
			<td>Add to the tail</td>
		</tr>
		<tr>
			<td>Insert</td>
			<td>Insert someplace</td>
		</tr>
		<tr>
			<td>Delete</td>
			<td>Delete&nbsp;&asymp; Remove</td>
		</tr>
		<tr>
			<td>Remove</td>
			<td>Remove&nbsp;&asymp;&nbsp;Delete</td>
		</tr>
	</tbody>
</table>

## Start/Stop
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Open</td>
			<td>Open file</td>
		</tr>
		<tr>
			<td>Start</td>
			<td>Start workflow</td>
		</tr>
		<tr>
			<td>Launch</td>
			<td>Launch program or server</td>
		</tr>
		<tr>
			<td>Close</td>
			<td>Close file</td>
		</tr>
		<tr>
			<td>Stop</td>
			<td>Stop workflow</td>
		</tr>
		<tr>
			<td>Pause</td>
			<td>Pause workflow which would start again</td>
		</tr>
		<tr>
			<td>Finish</td>
			<td>Workflow done</td>
		</tr>
	</tbody>
</table>

## Handle data from list
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Filter</td>
			<td>Filter data with conditions</td>
		</tr>
		<tr>
			<td>Merge</td>
			<td>Merge data with conditions</td>
		</tr>
		<tr>
			<td>Concat</td>
			<td>Add to the tail</td>
		</tr>
		<tr>
			<td>Split</td>
			<td>Split</td>
		</tr>
		<tr>
			<td>Deduplicate</td>
			<td>Remove duplicate</td>
		</tr>
		<tr>
			<td>Reverse</td>
			<td>Reverse</td>
		</tr>
		<tr>
			<td>Sort</td>
			<td>Sort</td>
		</tr>
		<tr>
			<td>Fill</td>
			<td>Overwrite data</td>
		</tr>
	</tbody>
</table>

## Common verbs
<table class="table table-bordered table-striped table-condensed">
	<tbody>
		<tr>
			<td>Parse</td>
			<td>Parse to a specific format, parse and extract content</td>
		</tr>
		<tr>
			<td>Analyse</td>
			<td>Data that can&nbsp; not easily get</td>
		</tr>
		<tr>
			<td>Convert</td>
			<td>Convert to another type</td>
		</tr>
		<tr>
			<td>Format</td>
			<td>Format data</td>
		</tr>
		<tr>
			<td>Validate</td>
			<td>Data&nbsp;Verification</td>
		</tr>
		<tr>
			<td>Ensure</td>
			<td>Validate the&nbsp;expected value</td>
		</tr>
		<tr>
			<td>Compose</td>
			<td>Compose multiple parts to a result</td>
		</tr>
		<tr>
			<td>Encode</td>
			<td>Encode</td>
		</tr>
		<tr>
			<td>Decode</td>
			<td>Decode</td>
		</tr>
		<tr>
			<td>Encrypt</td>
			<td>Encrypt</td>
		</tr>
		<tr>
			<td>Decrypt</td>
			<td>Decrypt</td>
		</tr>
		<tr>
			<td>Backup</td>
			<td>Backup</td>
		</tr>
		<tr>
			<td>Restore</td>
			<td>Restore</td>
		</tr>
		<tr>
			<td>Import</td>
			<td>Import from a special format file</td>
		</tr>
		<tr>
			<td>Export</td>
			<td>Export to a special format file</td>
		</tr>
		<tr>
			<td>Compress</td>
			<td>Compress</td>
		</tr>
		<tr>
			<td>Decompress</td>
			<td>Decompress</td>
		</tr>
	</tbody>
</table>
<br>

# Functions
Clean functions should be small and do only one thing

## Parameters
Keep the number of parameters small. Use a dictionary or Object to group multiple parameters

## Level of abstraction
Do not mix levels of abstraction in a function
```javascript
// Need to understand and interpret the different steps
if(!email.includes('@')) {
  console.log('Invalid email');
} else {
  const user = new User(email);
  user.save();
}
```

```javascript
// Just need to read the different steps
if(!isEmail(email)) {
  showError('Invalid email');
} else {
  saveNewUser(email);
}
```

## Pure functions

- Same input always returns same result

- No side effects during execution(console, change the external data, API calling)

```javascript
// Not a pure function
function connectDB() {
  const didConnect = database.connnect();
  if(didConnect) {
    return true;
  } else {
    console.log('Could not connect to database!');
    return false;
  }
}
```

```javascript
// Optimize to a pure function
function initApp() {
  const success = connectDB();
  if(!success) {
    console.log('Could not connect to database!');
  }
  // ...
}

function connectDB() {
  const didConnect = database.connnect();
  return didConnect;
}
```

## Test driven functions

```javascript
// Hard to test the method partially
function addProduct(name, price) {
    if(!name || name.trim() === '' || !price || price < 0 ) {
        console.log('Invalid input - product was not created.');
        return;
    }
    
    const product = {
        id: name + '-' + Math.random().toString(),
        name: name,
        price: price
    };
    database.insert('products', product);
    return product;
}
```

```javascript
// Split each process
function addProduct(name, price) {
    validateProductData(name, price);

    const savedProduct = saveProduct(name, price);
    return savedProduct;
}

function validateProductData(name, price) {
    if(!inputIsValid(name, price)) {
        throw new Error('Invalid input - product was not created.');
    }
}

function inputIsValid(name, price) {
    return !isEmpty(name) && hasMinValue(price, 0);
}
```

## Do not use boolean parameters

```javascript
// Call methods, hard to understand
printWelcomeWords(true);
calFinalAmount(200, true);

function printWelcomeWords(isActivated) {
    if (isActivated) {
        console.log('Welcome! Please select your product.');
    } else {
        console.log('Welcome! Please activate your account.');
    }
}

function calFinalAmount(originalAmount, isChild) {
    if (isChild) {
        return originalAmount * 0.5;
    } else {
        return originalAmount;
    }
}
```

```javascript
// Call methods, easy to understand
printWelcomeWordsOnActivated();
calFinalAmountForChild(200);
calFinalAmountForAdult(200);

function printWelcomeWordsOnActivated() {
    console.log('Welcome! Please select your product.');
}

function printWelcomeWordsOnUnactivated() {
    console.log('Welcome! Please activate your account.');
}

function calFinalAmountForChild(originalAmount) {
    return originalAmount * 0.5;
}

function calFinalAmountForAdult(originalAmount) {
    return originalAmount;
}
```
<br>

# Objects

## Law of Demeter
- Method within a class only interact with its direct friends
  - The variables, method parameters and method return objects within the class
- The local variables are not direct friends.

```java
// Violates the Law of Demeter, interact with local variable: Employee
public class Company {
    private Manager manager = new Manager();
    
    public void printEmployees(String name) {
        List<Employee> employeeList = manager.getEmployees(name);
        for(Employee employee : employeeList) {
            System.out.println(employee.getName());
        }
    }
}
```

```java
// Follows the Law of Demeter.
public class Company {
    private Manager manager = new Manager();
    
    public void printEmployees(String name) {
        manager.printEmployee(name);
    }
}
```

## SOLID principle
- 'S' and 'O' make code clean
  - Single responsibility Principle
    - each class does one thing, as small as possible
  - Open-closed Principle
    - a class should be open for extension but closed for modification
    - Reduce redundant code
- High cohesion
  - how well the methods of a class are using the class properties

## Strategy design pattern

```javascript
let mapCalculate = {
    'add': function (num1, num2) {
        return num1 + num2;
    },
    'sub': function (num1, num2) {
        return num1 - num2;
    },
    'mul': function (num1, num2) {
        return num1 * num2;
    },
    'div': function (num1, num2) {
        return num1 / num2;
    },
}

function calculate(command, num1, num2) {
    return mapCalculate[command](num1, num2);
}
```

```javascript
class Calculator {
    constructor() {
        this.strategy = null;
    }
    
    // Strategy can be changed dynamically
    setStrategy(strategy) {
        this.strategy = strategy;
    }
    
    calculateResult(num1, num2) {
        return this.strategy.execute(num1, num2);
    }
}

class Add {
    execute(num1, num2) {
        return num1 + num2;
    }
}

class Sub {
    execute(num1, num2) {
        return num1 - num2;
    }
}

//...
```
<br>

# Tips

## Lines
Keep lines short

## Comments
- Good code does not need too many comments
- Only use when:
  - Explanations that can’t be replaced by good naming 
  - Warnings 
  - Todo notes


## Elegant string concatenation
```javascript
// C++: snprintf, stringstream
// C#: string.Format
// Java: String.format

let userId = 'foo';
let userName = 'bar';
let userInfo = 'User Info: Id: ${userId} Name: ${userName}.';
let headerContent = 'start | ${userId} | ${userName} | end';
```

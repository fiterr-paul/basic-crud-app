# Paul Meier - Assessment Workbook (T3A1)

Workbook for Coder Academy Term 3 MERN Project


## Author
| [![Paul Meier](/docs/paul-meier-70px-70px.jpg)](https://github.com/fiterr-paul) |
|-----------|
| Paul Meier |


# Assessment Questions


## Question 1
Provide an overview and description of a standard source control process for a large project.

### Answer
Source control (or version control) is the practice of tracking and managing changes to code. The codebase is usually stored in a SCM (Source Control Management) system which will help to track and manage code that is uploaded/pushed from multiple sources/developers. The SCM system will help to track code changes, historical changes/revision, different versions of the codebase at different points in the development process and enable collaboration between multiple developers – each with their own versions of the codebase which can later be merged together after detectable conflicts are resolved.


## Question 2
What are the most important aspects of quality software?

### Answer
*** insert answer here ***


## Question 3
Outline a standard high-level structure for a MERN stack application and explain the components.

### Answer
A MERN stack application is comprised of four main technologies – Mongo, Express, React and Node. 

MongoDB
Mongo is a document-orientated “NoSQL” database program. It is used to store information in documents (in JSON format) – as opposed to a traditional SQL database which uses relational tables.

Node & Express
Node is a JavaScript environment with libraries that make it easier to write software. Express extends Node specifically to make it easier to create webservers. Therefore, Express is a server-side framework which is used for building web/mobile applications and API’s.

React
React is a JavaScript library/framework for building client-side user interfaces. This is the part of the application that is rendered in the user web browser and is how the user interacts with the application.

As stated, the user (client) interacts with the application via the user interface which is rendered to the users screen via the React framework. When the user/client triggers certain events, React will send or request data to/from the applications Server/Backend (Node/Express) API/s which are listening for incoming requests. The Server will then send a response/s back to the client – perhaps querying and saving data to the Mongo database first.


## Question 4
A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?

### Answer
*** insert answer here ***


## Question 5
With reference to one of your own projects, discuss what knowledge or skills were required to complete your project and to overcome challenges.

### Answer
*** insert answer here ***


## Question 6
With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project and suggest changes or improvements for future projects of a similar nature.

### Answer
*** insert answer here ***


## Question 7
Explain Control Flow, using an example from the JavaScript programming language.

### Answer
‘Control Flow’ is the order in which a computer executes statements in a script. A script in JavaScript may include several/many control structures such as conditionals, loops and functions.

The below If/Else Statement can change the flow of an application based on if a condition that is passed into the statement is determined to be true or false:

```javascript
if (condition === true) {
  return true
} else {
  return false
}
```


## Question 8
Explain Type Coercion, using examples from the JavaScript programming language.

### Answer
‘Type Coercion’ is the process of converting the value from one datatype into a different datatype. There are two different types of ‘Type Coercion’ – Implicit and Explicit.

‘Explicit’ Type Coercion is when type coercion is done on purpose by writing the appropriate code.
The following example will coerce the number 123 into a string (using the JavaScript built-in String function):
```javascript
const explicit = String(123)
console.log(explicit);
```

‘Implicit’ Type Coercion is when data types are converted automatically.
In the following example, the Number 123 will be coerced into a String that reads as “123”.
```javascript
const implicit = 123 + ''
console.log(implicit);
```


## Question 9
Explain Data Types, using examples from the JavaScript programming language.

### Answer
‘Data Types’ in JavaScript refer to the "type" of data being represented. There are several different types of data in JavaScript.

‘Primitive’ data types include type ‘String’, ‘Number’, ‘Boolean’, ‘Null‘ and ‘Undefined’. These data types are referred to as ‘Primitive’ because their values can contain only a single type (i.e.: a ‘String’ OR a ‘Number’, but NOT both combined).

The follow examples are 'primitive' types of data. Each individual data type can only be assigned to one variable:
```javascript
const string = 'string';
const number = 123;
const boolean = true;
let y = null;
let x = undefined;
```

A more complex data type in JavaScript would be an ‘Object’.
Objects are used to store collections of data and more complex entities. An example of a more complex entity might be an Object containing other data structures like an Array and even an Object containing other Objects.

The following example is an Object which contains 5 Key/Value pairs, one if which the value is another Object:
```javascript
const paulm = {
  name: 'paul meier',
  age: 38,
  gender: 'male',
  single: false,
  spouse: {kathys}
}
```


## Question 10
Explain how Arrays can be manipulated in JavaScript, using examples from the JavaScript programming language.

### Answer
*** insert answer here ***


## Question 11
Explain how Objects can be manipulated in JavaScript, using examples from the JavaScript programming language.

### Answer
*** insert answer here ***


## Question 12
Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language.

### Answer
*** insert answer here ***


## Question 13
For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and classes.

### Answer
*** insert answer here ***



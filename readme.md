# Paul Meier - Assessment Workbook (T3A1)

Workbook for Coder Academy Term 3 MERN Project


## Author
| [![Paul Meier](/docs/paul-meier-70px-70px.jpg)](https://github.com/fiterr-paul) |
|-----------|
| Paul Meier |


# Assessment Questions


## Question 1
__Provide an overview and description of a standard source control process for a large project.__

### Answer
Source control (or version control) is the practice of tracking and managing changes to code. The codebase is usually stored in a SCM (Source Control Management) system which will help to track and manage code that is uploaded/pushed from multiple sources/developers. The SCM system will help to track code changes, historical changes/revision, different versions of the codebase at different points in the development process and enable collaboration between multiple developers – each with their own versions of the codebase which can later be merged together after detectable conflicts are resolved.
Developers will typically work on their own forks and branches and commit their code for review by senior developers.


## Question 2
__What are the most important aspects of quality software?__

### Answer
Amongst what would be an endless list of aspects that encompasses “quality software”, here is a list of 5 general aspects that would be of high priority when it comes to quality software.

Testing
Making sure that the software (or components of the software) work as expected.

Scalability
Is the software engineered to be capable of growing to support the size of its increasing userbase.

Maintainability
Can the software be easily maintained by its engineers, code refactored and implemented without causing significant interruption to users.

Performance – As the userbase increases, and/or new features implemented, has the software been engineered for maximum speed no matter how large the userbase. Server processing power will also play a role here.

Security – Is the software secure against cyber-attacks and service disruption, information theft and identity theft.


## Question 3
__Outline a standard high-level structure for a MERN stack application and explain the components.__

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
__A team is about to engage in a project, developing a website for a small business. What knowledge and skills would they need in order to develop the project?__

### Answer
Firstly, the dev team (or project manager or business analyst) would need to meet with the client in order to assess the business requirements of the website or web application.

This would help determine what technologies need to be used to develop a website or application so that it would meet the businesses requirements - now and also perhaps into the future (referring to future scalability).

Depending on what the website or web application requirements are – a static website could easily be done with HTML, CSS and JavaScript, perhaps even using a Framework/Library such as React.

If a web application is required, full knowledge of MERN stack  or similar server-side / client-side application design would be required.
The team would need to produce technical documentation such as ERD charts, User-flow diagrams as well as UI and UX designs wireframes and low or high-fidelity designs.

Working as a team, a Source Control Process and Source Control Management solution would need to be implemented so as to keep the development process and codebase managed.

Also, depending on the size/scope of the project, the team would also need to determine what development methodology to be suitable for the project.
A smaller project might benefit more from ‘Rapid Application Development’ methodology as opposed to a ‘DevOps Deployment’ methodology.


## Question 5
__With reference to one of your own projects, discuss what knowledge or skills were required to complete your project and to overcome challenges.__

### Answer
A project that I worked on earlier in the course was a web application built with Ruby On Rails. Of course, the biggest aspect of this project was learning the Object Orientated language ‘Ruby’. Being my first programming language also meant that it was my biggest obstacle.

Apart from Ruby, learning Rails was also quite an undertaking and a challenge. Having only ever worked with HTML and CSS, I really found the concepts of OOP difficult and making sense of how it all fit into the Rails Framework.

One concept and technology I believe I had a good handle on was Postgres and SQL relational databases. Having had previous experience with deploying Content Management Systems such as WordPress meant that I have prior knowledge of relational database design and implementation.



## Question 6
__With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project and suggest changes or improvements for future projects of a similar nature.__

### Answer
With reference to one of your own projects, evaluate how effective your knowledge and skills were for this project and suggest changes or improvements for future projects of a similar nature.

One of the very first projects that I worked on during the Gen Tech Bootcamp was the Personal Portfolio website. This was primarily a personal website which was written using only HTML and CSS.

Having had many years of previous experience working on my own hobby website, I found that I excelled during this project. I received a lot of affirmations that the way I was coding HTML and CSS was indeed how it was supposed to be done by professional developers. I found this to be very rewarding after spending many years learning by myself.

One improvement I have made – and definitely something I have changed – is that I now code SCSS and strict HTML5. I find this to be much more efficient than using older HTML syntax and plain CSS.

Another improvement I have made is the addition of using more JavaScript in the client browser for small things that I previously had tried to do with CSS. I have been able to make my static websites much more visually dynamic.


## Question 7
__Explain Control Flow, using an example from the JavaScript programming language.__

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
__Explain Type Coercion, using examples from the JavaScript programming language.__

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
__Explain Data Types, using examples from the JavaScript programming language.__

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
__Explain how Arrays can be manipulated in JavaScript, using examples from the JavaScript programming language.__

### Answer
An Array is a data structure in which data can be stored, accessed, manipulated/mutated and deleted. To accomplish this in JavaScript, the array needs to be iterated through while using the appropriate array method for the desired outcome.

```javascript
let fruits = ['apple', 'banana', 'orange', 'pear', 'pineapple'];

// Example 1 – Add data to the array (mutates the original array):
fruits.push('Kiwi');
console.log(fruits);

// Example 2 – Delete data from the array (mutates the original array):
fruits.pop();
console.log(fruits);

// Example 3 – Access data in the array and log to console:
fruits.forEach(printArray = (fruit) => {
  console.log(fruit);
});

// Example 4 – Creates a new array from the original array (does not mutate the original array):
const newFruitsArrary = fruits.map(fruit => {
  return fruit
});
console.log(newFruitsArrary);
```


## Question 11
__Explain how Objects can be manipulated in JavaScript, using examples from the JavaScript programming language.__

### Answer
The below Object is referred to as an ‘Object Literal’. This example of a single Object is a data structure made up of key: value pairs. It has 4 properties – name, gender, rank and starship:
```javascript
const captain = {
  name: 'james t. kirk',
  species: 'human',
  rank: 'captain',
  starship: 'uss enterprise'
}
```

To access the keys/values in this Object and log it to console using string interpolation, I would write the following code:
```javascript
const name = captain.name
const species = captain.species
const rank = captain['rank']
const starship = captain['starship']

console.log(`This is ${rank} ${name} of the Federation starship ${starship}. I am ${species}.`);
```

To create more instances of an Object, a Constructor function is required. Using ES6 syntax, I would do this using the Class function to create more instances of the ‘Captains’ object:
```javascript
class Captains {
  constructor(name, species, rank, starship) {
    this.name = name;
    this.species = species;
    this.rank = rank;
    this.starship = starship;
  }
}

const pike = new Captains('christopher pike', 'human', 'captain', 'uss enterprise', );
console.log(pike);

const picard = new Captains('jean-luc picard', 'human', 'captain', 'uss enterprise', );
console.log(picard);
```


## Question 12
__Explain how JSON can be manipulated in JavaScript, using examples from the JavaScript programming language.__

### Answer
JSON (JavaScript Object Notation), is a format in which data can be stored in an organized, easy-to-access manner.

The JSON.stringify() function converts a JavaScript Object into a JSON string. This is useful for when the data needs to be available via API to be accessible by other servers/clients.

In the below example, the “JSON.stringify()” function is used on a JavaScript Object to convert it to a JSON string, then stored in a variable:
```javascript
const contacts = {
  name: "freddy kruger",
  age: 38,
  address: {
    street: "1 elm street",
    city: "hell"
  },
  interests: ["killing", "slashing"]
}
const data = JSON.stringify(contacts)
console.log(data);
```

To access data provided in JSON format via an API - or a file that has been “required” into a document, the JSON.parse() function is used.
In effect, this is the reverse process, in that a JSON String is now being converted into a JSON Object.

In this example, the JSON String (stored in the variable 'data') is now being parsed back into an Object:
```javascript
const newContacts = JSON.parse(data);
console.log(newContacts);
```


## Question 13
__For the code snippet provided below, write comments for each line of code to explain its functionality. In your comments you must demonstrates your ability to recognise and identify functions, ranges and classes.__

### Answer
```javascript
class Car {  // this is a class that will produce 'Car' objects
  constructor(brand) {  // the constructor will initialize the new object
    this.carname = brand;  // this assigns brand to this.carname
  }
  present() {  // this is a function named 'present'
    return 'I have a ' + this.carname;  // the function returns a string concatinated with the carname/brand
  }
}

class Model extends Car {  // this class inherits from the Car class
  constructor(brand, mod) {  // the constructor will initialize a model with a brand and model
    super(brand);  // this calls the car class
    this.model = mod;  // this assigns mod to this.model
  }
  show() {  // this function will return this.present from Car and concationate it with this.model
    return this.present() + ', it was made in ' + this.model;
  }
}

let makes = ["Ford", "Holden", "Toyota"]  // this is an array containing 3 items
let models = Array.from(new Array(40), (x,i) => i + 1980)  // this creates an array of numbers representing dates from 1980

function randomIntFromInterval(min,max) { // min and max included
    return Math.floor(Math.random()*(max-min+1)+min);  // this function returns a random integer between min and max
}

for (model of models) {

  make = makes[randomIntFromInterval(0,makes.length-1)]  // selects a random integer between 0 and makes.length-1 and uses that as an index to select a random make
  model = models[randomIntFromInterval(0,makes.length-1)]  // selects a random integer between 0 and makes.length-1 and uses that as an index to select a random model
    
  mycar = new Model(make, model);  // create a new Model object stored in the variable 'mycar'
  console.log(mycar.show())  // logs to the console 'I have a Ford, it was made in 1981' (assuming that Ford and 1981 was randomly chosen)
}
```

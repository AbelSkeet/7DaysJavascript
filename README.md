# 7 Days of Code - Programming Logic with Javascript

## Day 1

#### Exercise

Today we will start in a quiet way, but with a very important learning to move on to the next few days of challenges!

In case you haven't gone through this yet, it is very common when using Javascript to have problems with the types of variables when assigning new values ​​and comparing them.

Therefore, you will **rewrite the code below so that it is printing the information correctly, which makes sense and without errors**:

```javascript
let numberOne = 1
let stringOne = '1'
let numberThirty = 30
let stringThirty = '30'
let numberTen = 10
let stringTen = '10'

if (numberOne = stringOne) {
  console.log('The variables numberOne and stringOne have the same value, but different types')
} else {
  console.log('The variables numberOne and stringOne do not have the same value')
}

if (numberThirty == stringThirty) {
  console.log('The variables numberThirty and stringThirty have the same value and type')
} else {
  console.log('The variables numberThirty and stringThirty do not have the same type')
}

if (numberTen === stringTen) {
  console.log('Variables numberTen and stringTen have the same value, but different types')
} else {
  console.log('Variables numberTen and stringTen do not have the same value')
}
```

#### Tip

**You can use the browser itself to run your program** if you are not yet familiar with code editors, such as Visual Studio Code
To do this, just right-click on any page, go to `console` and type your code, very simple

If you want to **change the names of variables and values**, feel free, but never print something that is not true, huh!

#### Extra

To learn more about **comparison operators**, take a look at [this article](https://www.alura.com.br/artigos/operadores-matematicos-em-javascript?gclid=Cj0KCQiA_8OPBhDtARIsAKQu0gYUqZqgonpXyEP1_hpUl58wYAk_P3Ze4VWrxo9ftkFW9CLYOMyjO1caAlrcBE)

Take the opportunity to also study Javascript in [Alura courses](https://www.alura.com.br/cursos-online-front-end/javascript)

## Day 2

#### Exercise

Do you know when you register on a website and soon after, when you log in, it already calls you by your own name? In today's challenge we will do that!

You will need to develop a little program that will simulate one of these sites and **it will ask the person who is going to use it to answer 3 questions**:
`What's your name?`
`How old are you?`
`What programming language are you studying?`

And, clearly, the person using the program must **answer each one as they are made**

At the end, the program will **print the message:**

`"Hello X, you are X years old and already learning X!"`

Where each `X` is one of the answers given by the person

#### Tip

You can **add as many questions as you want**, including adding the person's answers in the message that will be printed

To **print and receive values**, you can either use `console.log`, `prompt` and `alert`, or use HTML and CSS if you already know these two technologies

#### Extra

To learn more about **prompt** and **alert**, take a look at [this site](https://www.devmedia.com.br/alert-em-javascript/37208)

Take the opportunity to also study Javascript in [Alura courses](https://www.alura.com.br/cursos-online-front-end/javascript)

## Day 3

#### Exercise

Have you ever played a game where he gave you more than one choice and depending on which one you chose, the character's fate would be totally different?

Let's do an example with Javascript!

Your challenge today is to **create the possible destinations of a game**, in which the player can choose:

1. At the **beginning** of your studies, where you can choose between **go to the front-end area** or **go to the back-end area**

2. In the **middle**, where if she is in the **front-end** area, she can **keep learning React** or **keep learning Vue** and, if she is in the **back area -end**, you can **keep learning C#** or **keep learning Java**

3. At the **end**, where, regardless of her previous choices, she will be able to choose between **continue specializing in the chosen area** or **continue developing to become a fullstack**

The important thing is that the person who plays can always **choose which decision to make** to be able to learn and develop in the programming area

#### Tip

You can already have an idea of ​​how to make this whole story happen, right? Especially remembering how we use **conditional structures in Javascript**!

If you still don't know how to **print and receive values** on web pages with HTML and CSS, you can use `console.log`, `prompt` and `alert` to develop your game

Remember you can always **customize** the game however you want!

#### Extra

To learn more about **conditional frameworks in Javascript**, take a look at [this site](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else )

Take the opportunity to also study Javascript in [Alura courses](https://www.alura.com.br/cursos-online-front-end/javascript)

## Day 4

#### Exercise

Have you ever played trying to guess the number your friend was thinking of? Because today you will play this game against the computer itself!

Here's everything you need to do for today's challenge:

You must create a little program that **already initializes with a specific value between 0-10 for the number you are going to guess**
Then he'll ask you **what value do you want to guess** and, if you get it right, he'll **congratulate you** or, if you're wrong, he'll **give you 2 more tries**
In the end, if you don't get it right, it will **print what the initial number was**

#### Tip

Think carefully about which **repetition structure** you will use to make your program run until the 3 attempts are over or the person hits the number

Remember that you can always **customize** your little program however you want!

#### Extra

You can even increment your program and make the machine itself choose the number to guess, using something called `Math.random()`, which you can check [on this site](https://developer.mozilla.org/ en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)

To learn more about **looping structures**, take a look at [this site](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

Take the opportunity to also study Javascript in [Alura courses](https://www.alura.com.br/cursos-online-front-end/javascript)

## Day 5

#### Exercise

Have you ever gone to the supermarket and taken a shopping list, but as you wrote everything down in the order you remembered, you had to get an apple in the fruit area, then a milk in the dairy area and then a pear again in the fruit area and stayed in this back and forth all over the place to complete the list?

Once you solve today's challenge, you definitely won't be doing that anymore!

What should you do then:

To facilitate your trip to the supermarket, you will create a program in Javascript, where it will **ask if you want to add a food to the shopping list** for you to answer with `yes` or `no`.
Then it will **ask you which food you want to insert** and you will type its name, such as `potato`.
Then, he should **ask which category this food fits in**, with pre-defined options, such as `dairy`, `frozen`, `sweets` and whatever else he finds interesting, so he can separate everything in its proper place. group
Finally, if you no longer want to add anything to the shopping list and answer `no` to the first question, it will **print a list with all items grouped**, as follows:

If you add to your list:
`banana`, `milk powder`, `tomato`, `vegetable milk`, `gum`, `bear candy`, `apple`, `grape`, `avocado` and `cow's milk`

The program should print, for example:

`Shopping list: banana, tomato, apple, grape, avocado, powdered milk, plant-based milk, cow's milk, gum and teddy bear'

#### Tip

We have an object within the javascript language that is used precisely to create lists of elements, called array. Use and abuse it!

Remember that you can always **style** your little program the way you want, including using other technologies for this, such as HTML and CSS. But this is **not mandatory** on our list of Javascript programming logic, so as I mentioned in previous days, you can use resources like `console.log`, `alert` and `prompt` to develop your program

#### Extra

To learn more about **arrays in Javascript**, take a look at [this site](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

Also don't forget to concatenate the different lists of categories into one at the end, for that you can read [this site](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/First_steps/ Strings)

Take the opportunity to also study Javascript in [Alura courses](https://www.alura.com.br/cursos-online-front-end/javascript)

## Day 6

#### Exercise

Remember yesterday, when we created a little program to create our own shopping list? Well, today our challenge is to make it even cooler!

You must create the option to **delete an item from the list**, which will be displayed next to the question of **do you want to add a food to the shopping list?**
From there, the program will **print the elements present in the current list** and the person will have to **write which one he wants to remove**
After that, the program will **delete the element from the list** and **print confirmation that the item really isn't there anymore**
Finally, it will go back to its initial question cycle

#### Tip

Remember that the option to delete an item should only be available **from the moment there is at least one element in the shopping list**

You can search for the element that the person wants to delete the way you want, using **Javascript methods** for this or manually writing everything that will happen

Don't forget to always **customize** your little program the way you see fit!

#### Extra

To learn more about **methods for arrays in Javascript**, take a look at [this site](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

Take the opportunity to also study Javascript in [Alura courses](https://www.alura.com.br/cursos-online-front-end/javascript)

## Day 7

That was quite a week, right? We practice a lot about programming logic with Javascript, but there is still one very important thing missing: **organize our code**

And yes, this is something mandatory to learn as a developer, because at one time or another in your career you will need to maintain your created code, or even fix something in the code that someone else wrote. Just imagine if this code is all messed up?

A good practice is to always separate each snippet of your code that will perform some specific function into even smaller blocks of code, but which can be reused and called at any other time throughout your program. These are called **functions**

#### Exercise

Have you ever stopped to think about how a calculator works?

It asks you to enter a number, then you select a type of operation with another number and it does the calculation itself to show you the result! Amazing right?

And then our last challenge will be to create our own calculator, but with a very important detail: **each operation must be a different function in our code**

The person must **choose an operation option printed by the program on the screen**, then he/she must **insert the two values ​​he/she wants to use** and the program must **print the result**

The available options should be: `sum`, `multiplication`, `division`, `subtraction` and `exit`, and in the latter the program should stop executing, showing a message "until next time"

#### Tip

Each operation must be a different **function** in our code, which will receive the values ​​entered as **parameters** and **return** the result of the operation

Don't forget to use **repeat structures** to make the calculator print the choice of operation until the person wants to stop the program

Also remember that in addition to `if` and `else` we also have the `switch`, very interesting to use in cases like this, multiple choice

**Customize your calculator** however you like!

#### Extra

To learn more about **functions in Javascript**, take a look at [this site](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

If you haven't studied `switch` yet, check out [this site](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/switch)

Take the opportunity to also study Javascript in [Alura courses](https://www.alura.com.br/cursos-online-front-end/javascript)


 # javaScript
## javaScript Basics

- HTML creates the content
- CSS changes the apearance
- JS makes it interactive

- to create pop up
```js
alert('hello');
```
or
```js
alert('Good Job');
```
- javaScript provides mathematics calculation on console

```js
2+2
```
or
```js
10-3
```
- to remove everything on page and show sms / to modify the webpage

```js
document.body.innerHTML = 'hello';
```
- syntax = rules that we have to follow in a programming language.

- homework 1
```js
alert('Good morning!');
alert('Abdur Rouf Robin');
10+5
20-5
2+2-5
document.body.innerHTML = 'Good morning!';
document.body.innerHTML ='Robin';
10+8+20
100-20-50+200
document.body.innerHTML = '';

```

## Numbers

- order of operations
  - BODMAS
  - we can't calculate % . we have to calculate manually 1% = 1/10
      - (..)
      - *, /
      - +, -
- 0.1 + 0.2 = 0.3000000000000004 // computer can't floating number properly
- to avoid this problem ---->> transform into integer (for dollar transform into cents) (to taka          transform into poisa)
- to round
    ```js
    Math.round(2.2)
    Math.round(2.3)
    Math.round((2095 + 799)*0.1)/100
    ```
### How to use Google
- mdn web docs javaScript
- chatgpt
- devdocs
-  homework
```js
//2a
1*10+3*8+1*5
//2b
(1*10+3*8+1*5)*3
//2c
(1850+750*2)/100
//2d
Math.round((1850+7.50*2)*0.1)/100
//2e
Math.round((1850+7.50*2)*0.2)/100
//2f
(2095+799+1899)/100
//2g
(2095+799+1899+499)/100
//2h
Math.round((2095+799+1899+499)*0.1)/100
//2i
(2095+799+1899+499)/100 + Math.round((2095+799+1899+499)*0.1)/100
//2j
Math.floor(2.8)
//2k
Math.ceil(2.2)
//2l
(25*9)/5+32
//2m
(86-32)*5/9
//2n
((-5)*9/5)+32
```
## String
- string = text
- syntax = '...'
- we can add string like
```js
'some' + 'text' //sometext
'some' + 'more' + 'text' //somemoretext
// this is called concatenation = combine strings together
```
- we can see the type of any value
```js
typeof 3
typeof 'hello'
```
- we can add number and string

```js
'hello' + 3 //hello3
//this is called type coercion or automatic type conversion
```
- practice
```js
'$' + 20.95 +7.99 //shows error
'$20.95' + 7.99 //shows error
'$' + ((2095+799)/100) //right
'$Items (' + (1 + 1) + '): $'+ (2095+799)/100
alert('$Items (' + (1 + 1) + '): $'+ (2095+799)/100);
```
- 3 ways to create string
  - single quote = '....' // better
  - double quotes = "...." // when we want to use single quote in string like I'm
     - escape character = \'
     - escape character = \"
     - escape character = \n //new line character
  - backtick = template string = // `....`
    - interpolation = insert value directly into string
    ```js
    `Items(${1+1}): $${(2095+799)/100}`
    ```
    - multi-line strings = strings are in multiple line
   
    ```js
    `some
    text`
    //'some\ntext'
    ```

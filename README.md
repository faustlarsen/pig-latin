# _Pig Latin_

#### _An app that converts any phrase into piglatin, October 28th, 2020_

#### By _**Taylor Baker, Constantine Yakubovski**_

## Description

_The purpose of this webpage is to convert any alpha input into an equivalent phrase in piglatin._

## Setup/Installation Requirements

* _This is a great place_
* _to list setup instructions_
* _in a simple_
* _easy-to-understand_
* _format_


## Known Bugs

_There are no known bugs at this time._

## Support and contact details

_If you would like to report a bug, please contact the developers._

* <taylorbaker.coding@gmail.com>
* 1(815)245-1234

## Technologies Used

#### Languages

 * _**HTML**_
 * _**CSS**_
 * _**JavaScript**_

#### Libraries

 * _**Bootstrap.css**_
 * _**jQuery-3.5.1.js**_

#### Tools

 * _**Git Bash**_
 * _**Visual Studio Code**_

### License

*This software is licensed under the MIT license.*

Copyright (c) 2020 **_Taylor Baker, Constantine Yakubovski_**



## Pig Latin

### How Pig Latin Works

Here are the rules of Pig Latin:

 - For words beginning with a vowel, add "way to the end.
 - For words beginning with one or more consonants, move all of the first consecutive consonants to the end, and add "ay".
 - If the first consonants include "qu", move the "u" along with the "q". Don't forget about words like "squeal" where "qu" doesn't come first!
 - For words beginning with "y", treat "y" as a consonant.

### Instructions

 1. Before writing any code, make a list of specs detailing each behavior your program will have. Start with the simplest possible behavior, and slowly move up in complexity.

 2. **Have at least two other pairs check your specs before you begin coding.** Ensure that each possible behavior is represented by a spec, and that they are ordered from simplest to most complex.

 3. Place your specs (and their example inputs and outputs) in your project's README.

 Now you're ready to start writing (and passing tests). Here's the process:

 1. Write a test for the simplest possible behavior. We will get you started:

  Describe: `pigLatin()`
  Test: "It will add 'way' to the end of words that begin with a vowel"
  Expect(pigLatin("a")).toEqual("away");

 2. Write the smallest amount of code needed to get the test passing.

 3. Test the code in the console, REPL, or JSFiddle.

 4. Once the test is passing, commit your code.

 Repeat the cycle above for each test. Do not move onto the next test until the previous one passes.

 Once you've completed your business logic, feel free to add a user interface with jQuery so you can run your application in the browser.

### Specs

  Describe: `pigLatin()`

  Test: "It will add 'way' to the end of words that begin with a vowel"
  Code: {the code we need to run to complete the test}
  Expect(pigLatin("a")).toEqual("away");

  Test: "It will move all consenents up to the first vowel to the back of the word it started on."
  Code: {the code we need to run to complete the test}
  Expect: {theCodeWeRun.toEqual(SomeValue)}

  Test: "After all front consenents have been moved to the back, it will add "ay" to the end of that word." 
  Code: {the code we need to run to complete the test}
  Expect: {theCodeWeRun.toEqual(SomeValue)}

  Test: "If the first consonants include "qu", move the "u" along with the "q".
  Code: {the code we need to run to complete the test}
  Expect: {theCodeWeRun.toEqual(SomeValue)}

  Test: "If there are no letters preceeding "y", treat it as a consonent. If there are letters preceeding "y", treat it as vowel."
  Code: {the code we need to run to complete the test}
  Expect: {theCodeWeRun.toEqual(SomeValue)}
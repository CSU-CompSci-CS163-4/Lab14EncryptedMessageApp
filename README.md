## Lab 12 - EncryptedMessageApp
 
## Scenario 
So far you have made a message app where a user can write a message, which can be stored to a file. The user can search through the messages by subject, sender, and receiver. To finish up the program, this week you will add another type of encryption, the `Substitution Cipher`. Instructions can be found in the [javadoc](http://www.cs.colostate.edu/~cs163/javadoc/lab14/package-summary.html).

The goal for this week is to explore polymorphism. Make sure to check the variables and methods for each class to see what you need to update.

Example of code running:

```text
Welcome to Wonderland Messenger.
[C]: compose new message
[S]: search for a message
[X]: exit
What would you like to do? c
TO:  Alice
FROM:  Hatter
SUBJECT:  Celebration
BODY:  Happy Un-birthday!!!
What file would you like to write your message to?  substitutionCipherExample.txt
Message composed.
Welcome to Wonderland Messenger.
[C]: compose new message
[S]: search for a message
[X]: exit
What would you like to do? c
TO:  Red
FROM:  Cheshire Cat
SUBJECT:  Glum
BODY:  Why so glum, queenie? You should smile more (:
What file would you like to write your message to?  caesarCipherExample.txt
Message composed.
Welcome to Wonderland Messenger.
[C]: compose new message
[S]: search for a message
[X]: exit
What would you like to do? c
TO:  Not the Hatter
FROM:  Not the Quick Rabbit
SUBJECT:  Not a subject
BODY:  Definitely not a message, definitely not from the Cheshire Cat.
What file would you like to write your message to?  noCipherExample.txt
Message composed.
Welcome to Wonderland Messenger.
[C]: compose new message
[S]: search for a message
[X]: exit
What would you like to do? x
Would you like to save your messages from this session? (y/n) y

Process finished with exit code 0

```

After running, `input.txt` looks like:
```text
TO: Alice
FROM: Hatter
SUBJECT: Red Queen
BODY: To keep ahead, run from the red queen.
TO: Hatter
FROM: Red
SUBJECT: New Hat
BODY: Hatter, I need a new hat, and if I don't get it, you won't need one.
TO: Cheshire Cat
FROM: Quick Rabbit
SUBJECT: Important Meeting
BODY: Don't be late for our very important date!
TO: Quick Rabbit
FROM: Cheshire Cat
SUBJECT: Directions
BODY: Am I going this way or that to meet you?
TO: Alice
FROM: Hatter
SUBJECT: Celebration
BODY: Happy Un-birthday!!!
TO: Red
FROM: Cheshire Cat
SUBJECT: Glum
BODY: Why so glum, queenie? You should smile more (:
TO: Not the Hatter
FROM: Not the Quick Rabbit
SUBJECT: Not a subject
BODY: Definitely not a message, definitely not from the Cheshire Cat.
```

The file `substitutionCipherExample.txt` looks like: 

``` text
TO: Alice
FROM: Hatter
SUBJECT: Celebration
BODY: 3lXXe G.-DFQ6o(le!!!
```

The file `caesarCipherExample.txt` looks like: 

``` text
TO: Red
FROM: Cheshire Cat
SUBJECT: Glum
BODY: ^o'zv'ns|t3'x|lluplF'`v|'zov|sk'ztpsl'tvyl'/A
```

The file `noCipherExample.txt` looks like: 

``` text
TO: Not the Hatter
FROM: Not the Quick Rabbit
SUBJECT: Not a subject
BODY: Definitely not a message, definitely not from the Cheshire Cat.
```

## Step 1: Getting Started
Take a look at the [javadoc](http://www.cs.colostate.edu/~cs163/javadoc/lab14/package-summary.html) and take note of what methods you need to create from scratch, which ones you need to modify from Lab 12, and which ones you already did and don't need to change. 

## Step 2: Implementation
Follow the [javadoc](http://www.cs.colostate.edu/~cs163/javadoc/lab14/package-summary.html) and write some code. Make sure to write tests for your code as you work on each method.

## Step 3: Finishing up
To turn in your assignment, click through the link on Canvas, upload your files to Zybooks and click submit for grading. Note you can do this more than once.

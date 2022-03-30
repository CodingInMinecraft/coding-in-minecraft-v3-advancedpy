# Advanced Coding using Python - Lesson 3.1 - Python - Comparing MakeCode to Python

### @explicitHints true


## Step 1 @unplugged

MakeCode is a code editor which allows you to code in both block-based and text-based formats.

We will now start to compare block-based and text-based coding.


## Step 2 @unplugged
**Switching from block-based to text-based coding in MakeCode**

MakeCode makes it very simple to change between the block-based and text-based coding in JavaScript or Python code views.

To change between the different views you can click the two buttons at the top of the screen. Click the drop-down to choose between JavaScript and Python.

![alt text](https://advancedpython.codingcredentials.com/Lesson3/3.1/images/1.png?raw=true "change")

## Step 3 @unplugged
**Comparing blocks to text**

When using block-based coding in MakeCode we create event handlers to respond to events happening in our Minecraft world - e.g.  when the player says a certain chat command or the player moves or a certain type of block is placed. 

We then place blocks which perform a series of actions in order.  

Each block typically performs a single action.

## Step 4 @unplugged
**Comparing blocks to text**

In text-based coding we have the same concept - we create code (an event handler) which will respond to an action happening in our Minecraft world (an event). 

In these event handler functions we then have a series of lines of code to perform a number of actions like each block in block-based coding.

![alt text](https://advancedpython.codingcredentials.com/Lesson3/3.1/images/2.png?raw=true "change")

## Step 5 @unplugged
**Comparing blocks to text**

Take a look at the previous example (shown again below) showing some block-based code alongside its text-based equivalent.

If we first look at the block-based code can you explain what it does?

When the player enters the word "demo" into the chat window the agent will move to the players position, move forward by one block, turn left, move forward by 3 blocks and finally place a block in front of them.

Now look at the Python equivalent of the blocks.

Can you see that there are a total of 7 lines of Python code. There are 6 blocks in the block-based version of the code and for each block there is a single line of Python code (we will explain the additional 7th line later).

![alt text](https://advancedpython.codingcredentials.com/Lesson3/3.1/images/2.png?raw=true "change")

## Step 6 @unplugged
**Comparing blocks to text**

Each line of Python is approximatley equivalent to a single MakeCode block. Scroll to the bottom of this page to learn more.

![alt text](https://advancedpython.codingcredentials.com/Lesson3/3.1/images/3.png?raw=true "change")

In the above graphic notice we have mapped the MakeCode blocks to their equivalent in Python.

The blue on chat command block is the event handler. All other blocks are contained within this blue block. 

In Python the equivalent of this block are lines 1 and 7 of the Python code. 

Line 1 is defining a function (named on_chat) which will contain the code that will run for the event handler.

Indentations or tabs at the beginning of a code line are very important in Python. 

In some other languages indentation is used to make code easier to read but in Python it is used to indicate a block of code. 

Therefore the 5 lines of code indented from lines 2 to 6 indiate that they are part of the on_chat function.

Line 7 is associating the function (on_chat) with the event of the player entering the chat command demo. 

We will explore the Python equivalent of these blocks later.

We will discuss functions later in Lesson 6.

## Step 7 @tutorialCompleted
Return to the game and move onto the Activity
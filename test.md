# 5024 Programming Test
Name:

This test evaluates your current programming skill set. You will be given 1 hour to complete this test. We are looking for efficient, neat code that can pass all test cases we give you.

On each question, you will be given two example test cases (input and expected output). We will then test your code with 10 cases (including the two you are shown). Because efficiency is very important, you will not get full marks if your code does not complete in under 1 second (unless otherwise specified).

You are allowed to use any programming language you would like, and working with other people is not allowed.

<!--In your code, make a variable at the top of your file, named `input` (unless otherwise specified). This is where we will put our input data, and your code must print the output (or return it, if using an assembly language)-->

Your code must have a function called `answer()`. Your code will be inside, or called by this function. We will pass in data to this function during the testing.


## Question 1 - Add it up!
For the first question, make your answer function take in two positive integers that will range from **1** to **100**. Your function should then add these numbers together to get the output. Your function should look like `answer(a, b)` (with variations depending on your language of choice). It should then print the output.

### Example test cases:

**Input 1:**

`answer(10,18)`

**Output 1:**

`28`

**Input 2:**

`answer(48, 42)`

**Output 2:**

`90`

## Question 2 - PID
One of the most important pieces of code used on the robot is the PID function. For this question, you do not have to know what PID is, we will give you a basic formula and all you have to do is return the correct value. You can assume that we did the rest of the work for you. Your `answer` function will be given 6 doubles (a number with decimal places). You will return the output of this formula: `(p*PGain + i*IGain + d*DGain)`. Your function should look like `answer(p, i, d, PGain, IGain, DGain)`.  Print your output once your function has finished.

### Example test cases:

**Input 1:**

`answer(10.00, 12.00, 5.40, 1.00, 1.00, 3.00)`

**Output 1:**

`38.2`

**Input 2:**

`answer(10.00, 12.00, 28.90, 0.00, 0.00, 0.00)`

**Output 2:**

`0.0`

## Question 3 - I have seen that before!
This question is a step up in difficulty. You will be given an array full of ints and an int showing the size of the array. Some of these numbers will repeat inside the array. Your function must print an array containing every number that appears more than once in the order that they were first found. Your function should look like `answer(array, size)`. Your output will be an array printed to the screen (If your language of choice does not support this, come talk to us and we will change your requirements).

### Example test cases:

**Input 1:**

`answer([10,20,20,5,56,65,34,10], 8)`

**Output 1:**

`[20, 10]`

**Input 2:**

`answer([1,5,5,8,4,6,2,8,5,7,3,5,77,48,6,2,34,6,74,8,3,3,0], 23)`

**Output 2:**

`[5, 8, 6, 2, 3]`

## Question 4 - Which auto are we doing?
During FRC PowerUp, at the beginning of the game, we had to figure out which sequence of code we had to run in order to successfully complete the autonomous portion of the game. Now, you are in charge of writing a function that can successfully tell our robot where it needs to go. Each game, the position of our "goal" was randomized, and the robot would also start in a different spot. You can assume that we have already done all the work of writing the different auto sequences. You will be given a 3 letter code, consisting of a mix of the letters: **R** and **L**. You must then print out a two letter code made up of the letters **R** (Right), **L** (Left), and **C** (Center) to tell the robot which code to run. Your function should look like `answer(game_data, robot_position)` and print a code that looks like `LC` to control the robot. Due to the fact that our robot could only use the low "goal", You will only need the first letter of `game_data`. During the actual game, we had less than 20ms to run this code, so make it fast! This is a trickier question, so three examples will be given and we will gladly help explain it to you differently if you require the assistance. Just raise your hand, or call one of us over.

**Input 1:**

`answer("LLL", "C")`

**Output 1:**

`LC`

**Input 2:**

`answer("RLR", "R")`

**Output 2:**

`RR`

**Input 3:**

`answer("RLR", "L")`

**Output 3:**

`RL`

## Question 5 - What is this??
This is the final question of the test! For this question, you are allowed to collaborate with anyone in the room and there is no time limit for your code to execute. We will accept the code or the answer. Or both. Be observant, and good luck from team **5024** .

```
<encrypted>
XGF2aXcgSWVyZSI2NTE7==
</encrypted>
```



# codefoo7
My application for Code Foo 7.  Contains answers to questions and links to repositories and media.

## 1) Youtube of me
Insert link to youtube here.

## 2) Lincoln Log Empire State Building Replica
##### Dimensions of Empire State Building: (Obtained from [wikipedia](https://en.wikipedia.org/wiki/Empire_State_Building))
* Height with antenna: 1454ft
* Height without antenna: 1250ft
* Length (east-west): 424ft
* Width (north-south): 187ft
* Total Volume: 1250 x 424 x 187 = 99,110,000ft

##### Basic Lincoln Log set (from [knex.com](http://www.knex.com/wranglers-ranch))
* Contains 86 pieces
* Average human male height 5.6 ft. (source google)

###### Estimated dimensions of basic set cabin based on included figure and average human male height
* Height: 3 figures x 5.6ft = 16.8ft
* Length: 2 figures x 5.6ft = 11.2ft
* Width: 1.5 figures x 5.6ft = 8.4ft (the perspective of the picture made this a bit tricky, appears to be a bit wider than the figure is tall.)
* Total Volume: 16.8 x 11.2 x 8.4 = 1580.544ft

##### Maths
```
1581/86 = 99110000/x
18.4 = 99110000/x
18.4x = 99110000
x = 99110000/18.4
x = 5386413.04347826
```
Estimated pieces (without antenna): 5,386,413

* height of antenna: 204ft
* height of long log piece: 2 figures or 11.2ft

Number of long logs to make an antenna: 204/11.2 = 18.214285714

Grand total 5,386,431 pieces

##### Final Answer
About 5.4 million pieces

## 3) Nuggle (Number Boggle)
This section has it's own [repo](https://github.com/thomas-j-sell/nuggle).  The explanation for design can be found there.

##### Can you make a version with a larger grid?
I can, in fact my solution is designed to be flexible enough to solve a puzzle of any size.

##### How well does it scale?
The following data is the average time in seconds it takes for my solution on my machine to solve a puzzle (average of 100 puzzles):
* 2x2 average execution time: 0.00015036
* 3x3 average execution time: 0.009666110000000004
* 4x4 average execution time: 21.244139600000008
* 5x5 average execution time: 1008.094548167 (limited to 9 completed runs)

It does not scale well.

## 4) Back End
This section has it's own [repo](https://github.com/thomas-j-sell/backend).

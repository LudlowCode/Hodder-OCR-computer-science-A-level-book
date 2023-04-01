# Hodder-OCR-computer-science-A-level-book
Useful related info for the book: different versions, errors, corrections, and solutions to questions.

This book is generally very useful, but in both editions I have there are some errors, hence this repo. 

Raising of issues, and submitting contributions is welcome, especially from A-level students and first-time open-source contributors.

*I am not affiliated with Hodder, OCR etc and make no gains from this.*

## Different versions
*There are two versions which look almost the same but one has far fewer errors. Let's call them Bad (more errors) and Good (fewer errors)*. To find out which one you have, look on the page before the contents page and the address of Hodder on the left. Bad = Euston Road and Good = Embankment. Now you know your version, you can look in the next section to find the errors.

## Errors
Firstly, a list of where the errors are. Maybe you could mark the pages as unreliable by highlighting the page numbers. If you enjoy a challenge, it might be fun to see if you can work out the errors yourself as you go, or if not, use the next section. This doesn't claim to be all the errors in the book; please raise an issue if you find a new error that needs to be added, and even better you could add it to this list and make a pull request to become a contributor to this open-source project.
### 'Bad' book errors
51, 59, 147, 148, 149, 150, 177, 178, 180.
### 'Good' book errors
51, 59, 148.
## Corrections
This section has a description of the necessary correction for each page. 
(followed by location of error in brackets)
### 51
Binary search on 100 items would be 10 checks, as log<sub>2</sub>1000 is about 10 (not 8). 
(75% of the way down the page)
### 59
Swap D and B (not C and B).
(75% of the way down the page)
### 147 
2 - 1 is 1 (not 0)
(the bit in the 2s column of the example at the top-left)
### 148
0 + 0 = 0 (not 1) *this is my favourite*
(in key points at the top of the page)
### 149
The mantissa is inconsistent in the final example. It should always be 111110.
(first and last lines of the example at the bottom)
### 150
It says 10-bit mantissa but there are only 9 bits. It doesn't matter to the demo, which is correct for the numbers used, so probably just leave it. But to be consistent with the good book, you would make it 10 bits. To do that, make sure the final 4 bits of the mantissa are the same at each step, i.e. either 0000 or 1111.
(example at the top)
### 177
1 + 1 has a sum of 0 and a carry of 1, so the final S should be 0 (not 1) in the half adder truth table. Thus, S can be provided by an XOR (not a NAND).
(truth table near the top of the page, third column, and the following paragraph)
### 178
The full adder uses OR not NOR for the two carries, so should not have the negation circle at the front.
(80% down the page circuit diagram)
### 180
The blue block should be four in height to encompass more 1s. Two reasons, firstly a block in a K map should be as big as possible, and secondly they must be rectangles of size 2^n^.
Also, the rogue 1 that is not in either block of the second example is suppposed to be 0.
(the two example K-maps in the top half of the page)
## Solutions to the questions
They are attached as PDF files in this repo.
## Pictorial corrections
These might be added at some stage.

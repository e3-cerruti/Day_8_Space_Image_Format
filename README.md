# Day 8: Space Image Format
___
_This activity comes from a project called [Advent of Code](https://adventofcode.com/2019/day/8). You may work with the input and solution in this project or you can create an account and use the input given to you on the site. I now return you to Advent of Code in progress..._
___
The Elves' spirits are lifted when they realize you have an opportunity to reboot one of their Mars rovers, and so they are curious if you would spend a brief sojourn on Mars. You land your ship near the rover.

When you reach the rover, you discover that it's already in the process of rebooting! It's just waiting for someone to enter a BIOS password. The Elf responsible for the rover takes a picture of the password (your puzzle input) and sends it to you via the Digital Sending Network.

Unfortunately, images sent via the Digital Sending Network aren't encoded with any normal encoding; instead, they're encoded in a special Space Image Format. None of the Elves seem to remember why this is the case. They send you the instructions to decode it.

Images are sent as a series of digits that each represent the color of a single pixel. The digits fill each row of the image left-to-right, then move downward to the next row, filling rows top-to-bottom until every pixel of the image is filled.

Each image actually consists of a series of identically-sized layers that are filled in this way. So, the first digit corresponds to the top-left pixel of the first layer, the second digit corresponds to the pixel to the right of that on the same layer, and so on until the last digit, which corresponds to the bottom-right pixel of the last layer.

For example, given an image 3 pixels wide and 2 pixels tall, the image data 123456789012 corresponds to the following image layers:

```
Layer 1: 123
         456

Layer 2: 789
         012
```
The image you received is 25 pixels wide and 6 pixels tall.

To make sure the image wasn't corrupted during transmission, the Elves would like you to find the layer that contains the fewest 0 digits. On that layer, what is the number of 1 digits multiplied by the number of 2 digits?
___
This activity fulfills the last part of the consumer review lab:
## Final Activity
### Description
This open-ended activity requires you to develop a program on a topic that interests you. As a class, spend a few minutes reviewing the requirements of the open-ended activity.

### Requirements
* Write a program with a main method
* Create at least one new method which is called from main that takes at least one parameter
* Call at least two distinct methods from the String class
* Utilize conditional statements or compound Boolean expressions
* Utilize iteration

### Recommendations
It’s strongly recommended that the implementation of the program involve collaboration with another student. __Your selected program can be anything that you choose that meets the requirements and allows you to demonstrate your understanding.__

Before beginning, make sure that you understand the expectations for the activity.

* Who will you be working with? Are you allowed to work with a partner? In a group ofthree or four?
* Among the members of your group (or with your partner), how will the implementationbe completed?
* If you’ll be using pair programming, will your teacher be instructing you when to switch driver and navigator, or is this something that you need to keep track of?
* What should you do if your group/pair is stuck? Does your teacher want you to come straight to them? Are you allowed to ask another group?

### Next Steps: Part 2

Once you have generated the correct result you may continue onto [part 2](PART2.md).

# Script

Alright, we're about to talk about significant figures, and make sure your brain is fully powered on because this one can be a little tricky. 

Okay, so what even IS the point of significant figures? Well, in short, they help us **not lie**.

...Not really. Actually, they keep us from making an estimate that is *too* precise for our measuring abilities. In other words, they tell us how precise our measuring tools are.

Let's say I have a wooden ruler and it can measure down to tenths of inches. Let's also say that I measured an exactly 7-inch pencil with it. 

The rules of significant figures say that we can only estimate a measurement one digit further than our measuring tool can accurately measure. So, when I write down this measurement, I should estimate to the hundredths place, because that's one digit further than our measuring tool can accurately measure. That means I should write this measurement as $7.00$. Not $7$, not $7.0$, not $7.000$; write it as $7.00$.

Alright, now that we've clarified that, how does one determine how many significant figures a number has? Well it's easy, you just gotta follow these four steps:

1. Any non-zero digit is a significant figure.
2. Any zeroes that are sandwiched between significant figures are also significant.
3. Zeroes on the left-hand side of (or before) all the significant figures aren't significant, ever.
4. Zeroes on the right-hand side of (or after) all the significant figures are significant IF there is a decimal point.

For people living in the Americas, there's a simpler way of thinking about it:

When looking at a map, the Pacific ocean is to the left of us, while the Atlantic Ocean is to the right of us. Cool, so if the decimal point is PRESENT, start from the left side of the number and go digit-by-digit until you hit a non-zero number, then begin counting all of the digits after that (including zeroes). 

HOWEVER, if the decimal point is, in fact, ABSENT, start from the right side of the number and do the same process until you hit a non-zero number, then just keep counting digits until you're at the end of the number.

Alright, got all that? Take a look at some practice problems:

$$ 0.00356 $$

Right off the bat, I see three non-zero numbers, so we have three sig figs so far. No zeroes are sandwiched between them, so nothing to worry about there. The zeroes before the non-zero numbers don't count, and there aren't any zeros afterwards, so we don't gotta worry 'bout nun. So, that's it; we have three sig figs!

$$ 30{,}700 $$
Alright, there are two non-zero numbers: three and seven. That's two sig figs so far. There's also a singular zero sandwiched between those numbers, so that's a total of three sig figs. No zeroes before and the zeroes after don't count because the decimal point is absent. So, it looks like we have three sig figs yet again.

$$ 003.040800 $$ 
Okay, there are two non-zero numbers: three, four, and eight. There are two zeroes sandwiched in between sig figs, so that adds two more to our total number of sig figs. The zeroes before the non-zero numbers never count, but the ones after DO count (because there decimal point is there!) so that adds another two to our count. So, we have a total of seven sig figs here!

Alright, cool. Now that we're good at identifying how many sig figs there are in a number, let's talk about how to figure out how many sig figs your answer needs once you've done some operations.

When dividing or multiplying two numbers together, you MUST round your answer to match the number with the fewest amount of sig figs. For example, let's look at this: $$0.0034 \times 305 = 1.037$$
My answer is $1.037$, but that's not properly rounded to the correct number of sig figs yet. Let's take a look at how many sig figs the factors had. $0.0034$ has two sig figs and $3050$ has three sig figs. We're gonna round our answer to match the fewer of the two, so we're gonna round $1.037$ to two sig figs, which makes our answer $1.0$.

Here's another example, with division: $$5.670 \div 0.0054 = 1050$$ 
We've got to round our answer to the lowest amount of sigfigs. Looking at the two numbers that we're dividing, we have either four sigfigs or two sigfigs. Two is smaller than four, so we should probably round our answer to two sigfigs. And so... 1050 rounded to two sigfigs is 1100.


Different story with adding and subtracting: when you add and subtract, you want to round to the fewest number of decimal places. Check this out: $$23.1 - 1.567 = 21.533$$  
My unrounded answer is $21.533$, but we have to round to the fewest number of decimal places between the two numbers we're subtracting. $23.1$ has one decimal place while $1.567$ has three decimal places. Therefore, our answer should be rounded to one decimal place. Thus, our final answer is $21.5$.

Here's another one: $$ 1.239 + 35.67 = 36.909 $$
1.239 has three decimal places while 35.67 has two. Thus, our final answer should be rounded to two decimal places, so our final answer is $36.91$.


## Check
Alright, here's the part of the video where we check if you're chilling. Feel free to pause the video at any moment if you need some more time. How many sigfigs does this number have? $$0.000000000060700$$
It has five sigfigs... six and seven are sigfigs, as well as that zero in between, as well as every zero after.

How about this one? $$14{,}005{,}100$$
You'll never believe it; it has six sigfigs!! There are four non-zero digits, two zeroes sandwiched in between, and the zeroes after the non-zeroes don't count because the decimal point is NOT here!

One more of this kind: $$500.6090$$
This one's got seven sigfigs... there are three non-zero digits, three sandwiched zeroes, and the zero after the sigfigs is a sigfig because the decimal point is present!


Alright, let's check out your rounding skills. I trust you know how to add and multiply, so I'll do that work for you... all YOU gotta do is round the answer! 

Try this: $$5.67 \times 4.5 = 25.515$$
What'd you get? Was it 26? I hope it was 'cause if it was you'd be correct!!! We wanna round to the lowest possible number of sigfigs given the two numbers we're multiplying together... so we're rounding to two sigfigs. $25.515$ rounded to two sigfigs is $26$!

Let's see if you've got this one: $$9.6 + 3.456 = 13.056$$
Did you get 13.1? If you did you did it!! This one's slightly different from the previous one because now we're adding as opposed to multiplying... they have completely different rules (if you don't remember them you should probably go back and do some research... or google it).

For this one, we're trying to round to the lower number of decimal places, which would be one, in our case. So rounding to one decimal place will give us 13.1! (Not 13.)
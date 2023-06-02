3 Ants and Triangle
There are 3 ants sitting on three corners of a triangle. All ants randomly pick a direction and start moving along the edge of the triangle. What is the probability that any two ants collide?


Collision doesn’t happen only in following two cases
1) All ants move in counterclockwise direction.
 
2) All ants move in clockwise direction.
 
Since every ant has two choices (pick either of two edges going through the corner on which ant is initially sitting), there are total 23 possibilities.
Out of 23 possibilities, only 2 don’t cause collision. So, the probability of collision is 6/8 and the probability of non-collision is 2/8.


Heaven and Hell
There are two gates, one to hell and the other to heaven. Two gatekeepers, one for each gate. One of them always speaks the truth and the other always lies but you don’t know which one guards which gate. You are allowed only one question and you need to find out the gate to heaven.
What is the question? 
 Solution: Ask any guard “What would the other guard say if I ask which way is to the hell ?” And whatever answer he give is the way to the heaven. Explanation: If you end up asking the question to the truthful one, he will speak the truth and he knows that other guard is going to lie so he will show the way to the heaven. If you end up asking the question to the liar, he will lie about the other and the answer will be the way to the heaven. 
Ask one of them: "Does the gatekeeper guarding the gate of heaven always speak the truth?"
If the gatekeeper says "No", the other gate is the gate to heaven. If he says "Yes", the gate he is guarding is the one.

Case 1:
Heaven gatekeeper speaks the truth and Hell's gatekeeper lies.
As per our question, Heaven's gatekeeper will reply "Yes",

Case 2:
Heaven gatekeeper lies and Hell's gatekeeper speaks the truth.
In this case, Heavens gatekeeper will again reply "Yes"

You are blindfolded and 10 coins are placed in front of you on the table. You are allowed to touch the coins but can’t tell which way up they are by feel. You are told that there are 5 coins head up, and 5 coins tails up but not which ones are which. 
Can you make two piles of coins each with the same number of heads up? You can flip the coins any number of times. 
ANSWER: 
Yes 
Explanation: 
Make 2 piles with an equal number of coins. Now, flip all the coins in one of the piles. 
Let’s consider a simple case: 
P1: H T T T T 
P2: H H H H T 
By flipping P1 
P1: T H H H H 
P2: H H H H T 
P1(heads) = P2(heads) 


 
3 Mislabeled Jars
July 12, 2013 9:55 pm | 8 Comments | crazyadmin
Puzzle:
This problem is also called Jelly Beans problem. This is the most commonly asked interview puzzle.
You have 3 jars that are all mislabeled. One jar contains Apple, another contains Oranges and the third jar contains a mixture of both Apple and Oranges.
You are allowed to pick as many fruits as you want from each jar to fix the labels on the jars. What is the minimum number of fruits that you have to pick and from which jars to correctly label them?
Labels on jars are as follows:
 

Puzzle Solution:
Let’s take a scenario. Suppose you pick from jar labelled as Apple and Oranges and you got Apple from it. That means that jar should be Apple as it is incorrectly labelled. So it has to be Apple jar.
Now the jar labelled Oranges has to be Mixed as it cannot be the Oranges jar as they are wrongly labelled and the jar labelled Apple has to be Oranges.
Similar scenario applies if it’s a Oranges taken out from the jar labelled as Apple and Oranges. So you need to pick just one fruit from the jar labelled as Apple and Oranges to correctly label the jars.
There are 3 jars, namely, A, B, C. All of them are mislabeled. Following are the labels of each of the jars:
•	A: Candies
•	B: Sweets
•	C: Candies and Sweets (mixed in a random proportion)
You can put your hand in a jar and pick only one eatable at a time. Tell the minimum number of eatable(s) that has/have to be picked in order to label the jars correctly.

 

 

Assume that the shape of the candies and sweets are identical and there is no way to differentiate them by touching alone



 
 
 








	
 
Give two boxes B1 and B2 one have 50 red marbles and other have 50 blue marbles. A ball is selected randomly from any of the box and the task is to maximize the probability of selecting a red ball, by reshuffling marbles in both the boxes.
Solution:
Let P(R) be the probability of picking a red marble.
P(R) = P(B1) * P(B1 | J1) + P(B2) * P(B2 | J2)
Here, P(B1) and P(B2) refers to selecting B1 and B2 and the probability of selecting each box is   J1 and J2 refers to number of total balls in B1 and B2 respectively.

If we do not reshuffle any balls. Then
P(R) = ((1 / 2) * 1) + ((1 / 2) * 0) = 0.5
But, If we decrease the number of red balls in box B1 and increase the number of red balls in box B2 then the probability of getting a red ball will be maximized.
Therefore, let us take 49 red marbles from B1 to B2 then there will be 1 red ball in B1 and 99 balls in B2 out of which 49 are red and 50 of them are blue in the second jar.
Then
P (R) = ((1 / 2) * (1 / 1)) + ((1 / 2) * (49 / 99)) = 0.747474
Hence,
the maximum probability of choosing a red ball is 0.747474

 
Prisoners and Hats Puzzle
August 13, 2013 10:51 am | 6 Comments | crazyadmin
Problem:
Four prisoners are arrested for a crime, but the jail is full and the jailer has nowhere to put them. He eventually comes up with the solution of giving them a puzzle so if they succeed they can go free but if they fail they are executed.
The jailer puts three of the men sitting in a line. The fourth man is put behind a screen (or in a separate room). He gives all four men party hats. The jailer explains that there are two black and two white hats; that each prisoner is wearing one of the hats; and that each of the prisoners is only to see the hats in front of them but not on themselves or behind. The fourth man behind the screen can’t see or be seen by any other prisoner. No communication between the prisoners is allowed.
If any prisoner can figure out and say to the jailer what color hat he has on his head all four prisoners go free. If any prisoner suggests an incorrect answer, all four prisoners are executed. The puzzle is to find how the prisoners can escape, regardless of how the jailer distributes the hats.
 
Solution:
Prisoner A and B are in the same situation – they have no information to help them determine their hat colour so they can’t answer. C and D realise this.
Prisoner D can see both B and C’s hats. If B and C had the same colour hat then this would let D know that he must have the other colour.
When the time is nearly up, or maybe before, C realises that D isn’t going to answer because he can’t. C realises that his hat must be different to B’s otherwise D would have answered. C therefore concludes that he has a black hat because he can see B’s white one.

 
 Tricky Probabilty Problem To Solve
Aishwarya was first to board to her flight to delhi.
She forgot her seat number and picks a random seat for herself.
After this, every single person who get to the flight sits on his seat if its available else chooses any available seat at random.
Abhishek is last to enter the flight and at that moment 99/100 seats were occupied.

Whats the probability what Abhishek gets to sit in his own seat ?
Solution:
1/2

one of two is the possibility
1. If any of the first 99 people sit in Abhishek seat, Abhishek will not get to sit in his own seat.
2. If any of the first 99 people sit in Aishwarya's seat, Abhishek will get to sit in his seat.
Measuring Glass Puzzle
There are 2 sand measuring glasses.
The small one can measure 5 hours and the large one can measure 7 hours.

How can we measure 16 hours with 2 sand measuring glasses running together ?
Solution:
Steps:
* Start both sand measuring glasses at the same time.
* You flip over the small sand hourglass when it finishes the first 5 hours.
* Flip over the large one when it finishes its first 7 hours.
* When the small sand hourglass runs to 10 hours, flip over the small and large sand hourglass at the same time. It means the large sand hourglass will run 3 hours again. When the large sand hourglass run to 13 hours (7 + 3 + 3), flip both the small and large sand hourglass over again to run another 3 hours.
Crossing The River In Minimum Time Puzzle
Four people need to cross a dark river at night.

* They have only one torch and the river is too risky to cross without the torch.
* If all people cross simultaneously then torch light wont be sufficient.
* Speed of each person of crossing the river is different.cross time for each person is 1 min, 2 minutes, 7 minutes and 10 minutes.

What is the shortest time needed for all four of them to cross the river ?
Solution:
17 min

The initial solution most people will think of is to use the fastest person as an usher to guide everyone across. How long would that take? 10 + 1 + 7 + 1 + 2 = 21 minutes. Is that it? No. That would make this question too simple even as a warm up question.

Let's brainstorm a little further. To reduce the amount of time, we should find a way for 10 and 7 to go together. If they cross together, then we need one of them to come back to get the others. That would not be ideal. How do we get around that? Maybe we can have 1 waiting on the other side to bring the torch back. Ahaa, we are getting closer. The fastest way to get 1 across and be back is to use 2 to usher 1 across. So let's put all this together.

1 and 2 go cross
2 comes back
7 and 10 go across
1 comes back
1 and 2 go across (done)

Total time = 2 + 2 + 10 + 1 + 2 = 17 minutes
 Logic Coins Puzzle
Assuming i have an infinite supply of coins.

What is the fewest number of coins would be required in order to make sure each and every coin touched exactly three other coins.
Solution:
Four

three placed flat on the table in a triangle(touching each other) and put the fourth one on top of them in the middle
Classic Lateral Thinking Problem
There are two glasses in front of you. One of the glasses is full of coke and the other glass is full of lemonade. You take a spoonful of coke and mix it into the glass of lemonade. Now the lemonade glass has a mixture of coke and lemonade. You take a spoonful of that mixture and mix it inside the coke glass.

Now what do you think? - The glass with coke has more quantity of lemonade or the glass with lemonade have more quantity of coke mixed with it?
Solution:
This problem can be solved with algebra as well as logical reasoning. We are going to tell you how it is logically possible.

Be it any quantity that was present in the beginning and any liquid as well. We know that we have taken a spoonful from one glass and put it into another. Then, we have taken a spoonful from the other glass and put it into the first glass. So, at the end of it, the quantity of liquid in either glass remains same as it was in the beginning.

Therefore, we can conclude the fact that any amount of coke that is missing in the glass with coke will be present in the lemonade glass. Also, the same quantity of lemonade will be missing from the lemonade glass and will be present in the coke glass.


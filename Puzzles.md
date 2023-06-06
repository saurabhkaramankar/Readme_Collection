# 3 Ants and Triangle
There are 3 ants sitting on three corners of a triangle. All ants randomly pick a direction and start moving along the edge of the triangle. What is the probability that any two ants collide?

Solution : 

Collision doesn’t happen only in following two cases
1) All ants move in counterclockwise direction.
 2) All ants move in clockwise direction.
 Since every ant has two choices (pick either of two edges going through the corner on which ant is initially sitting), there are total 23 possibilities.
Out of 23 possibilities, only 2 don’t cause collision. So, the probability of collision is 6/8 and the probability of non-collision is 2/8.

---

# Heaven and Hell
There are two gates, one to hell and the other to heaven. Two gatekeepers, one for each gate. One of them always speaks the truth and the other always lies but you don’t know which one guards which gate. You are allowed only one question and you need to find out the gate to heaven.
What is the question? 

Solution:

 Ask any guard “What would the other guard say if I ask which way is to the hell ?” And whatever answer he give is the way to the heaven. Explanation: If you end up asking the question to the truthful one, he will speak the truth and he knows that other guard is going to lie so he will show the way to the heaven. If you end up asking the question to the liar, he will lie about the other and the answer will be the way to the heaven. 
Ask one of them: "Does the gatekeeper guarding the gate of heaven always speak the truth?"
If the gatekeeper says "No", the other gate is the gate to heaven. If he says "Yes", the gate he is guarding is the one.
Case 1:
Heaven gatekeeper speaks the truth and Hell's gatekeeper lies.
As per our question, Heaven's gatekeeper will reply "Yes",
Case 2:
Heaven gatekeeper lies and Hell's gatekeeper speaks the truth.
In this case, Heavens gatekeeper will again reply "Yes"

---
# 10 Coins Puzzle

You are blindfolded and 10 coins are placed in front of you on the table. You are allowed to touch the coins but can’t tell which way up they are by feel. You are told that there are 5 coins head up, and 5 coins tails up but not which ones are which. 
Can you make two piles of coins each with the same number of heads up? You can flip the coins any number of times. 

Solution: 

ANSWER: Yes 
Make 2 piles with an equal number of coins. Now, flip all the coins in one of the piles. 
Let’s consider a simple case: 
P1: H T T T T 
P2: H H H H T 
By flipping P1 
P1: T H H H H 
P2: H H H H T 
P1(heads) = P2(heads) 

---

# 3 Mislabeled Jars

This problem is also called Jelly Beans problem. You have 3 jars that are all mislabeled. One jar contains Apple, another contains Oranges and the third jar contains a mixture of both Apple and Oranges.You are allowed to pick as many fruits as you want from each jar to fix the labels on the jars. What is the minimum number of fruits that you have to pick and from which jars to correctly label them?
Labels on jars are as follows:

Solution:

Let’s take a scenario. Suppose you pick from jar labelled as Apple and Oranges and you got Apple from it. That means that jar should be Apple as it is incorrectly labelled. So it has to be Apple jar.
Now the jar labelled Oranges has to be Mixed as it cannot be the Oranges jar as they are wrongly labelled and the jar labelled Apple has to be Oranges.
Similar scenario applies if it’s a Oranges taken out from the jar labelled as Apple and Oranges. So you need to pick just one fruit from the jar labelled as Apple and Oranges to correctly label the jars.
There are 3 jars, namely, A, B, C. All of them are mislabeled. Following are the labels of each of the jars:
•	A: Candies
•	B: Sweets
•	C: Candies and Sweets (mixed in a random proportion)
You can put your hand in a jar and pick only one eatable at a time. Tell the minimum number of eatable(s) that has/have to be picked in order to label the jars correctly.
Assume that the shape of the candies and sweets are identical and there is no way to differentiate them by touching alone

---
# Blue Marbles & Red Marbles
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

---

# Prisoners and Hats Puzzle
Four prisoners are arrested for a crime, but the jail is full and the jailer has nowhere to put them. He eventually comes up with the solution of giving them a puzzle so if they succeed they can go free but if they fail they are executed.
The jailer puts three of the men sitting in a line. The fourth man is put behind a screen (or in a separate room). He gives all four men party hats. The jailer explains that there are two black and two white hats; that each prisoner is wearing one of the hats; and that each of the prisoners is only to see the hats in front of them but not on themselves or behind. The fourth man behind the screen can’t see or be seen by any other prisoner. No communication between the prisoners is allowed.
If any prisoner can figure out and say to the jailer what color hat he has on his head all four prisoners go free. If any prisoner suggests an incorrect answer, all four prisoners are executed. The puzzle is to find how the prisoners can escape, regardless of how the jailer distributes the hats.

Solution:

Prisoner A and B are in the same situation – they have no information to help them determine their hat colour so they can’t answer. C and D realise this.
Prisoner D can see both B and C’s hats. If B and C had the same colour hat then this would let D know that he must have the other colour.
When the time is nearly up, or maybe before, C realises that D isn’t going to answer because he can’t. C realises that his hat must be different to B’s otherwise D would have answered. C therefore concludes that he has a black hat because he can see B’s white one.

---
 
# Tricky Probabilty Problem 
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

---

# Measuring Glass Puzzle
There are 2 sand measuring glasses.
The small one can measure 5 hours and the large one can measure 7 hours.
How can we measure 16 hours with 2 sand measuring glasses running together ?

Solution:

Steps:
* Start both sand measuring glasses at the same time.
* You flip over the small sand hourglass when it finishes the first 5 hours.
* Flip over the large one when it finishes its first 7 hours.
* When the small sand hourglass runs to 10 hours, flip over the small and large sand hourglass at the same time. It means the large sand hourglass will run 3 hours again. When the large sand hourglass run to 13 hours (7 + 3 + 3), flip both the small and large sand hourglass over again to run another 3 hours.

---

# Crossing The River In Minimum Time Puzzle
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

---

# Logic Coins Puzzle
Assuming i have an infinite supply of coins.What is the fewest number of coins would be required in order to make sure each and every coin touched exactly three other coins.

Solution:

Four
three placed flat on the table in a triangle(touching each other) and put the fourth one on top of them in the middle

---

# Classic Lateral Thinking Problem
There are two glasses in front of you. One of the glasses is full of coke and the other glass is full of lemonade. You take a spoonful of coke and mix it into the glass of lemonade. Now the lemonade glass has a mixture of coke and lemonade. You take a spoonful of that mixture and mix it inside the coke glass.
Now what do you think? - The glass with coke has more quantity of lemonade or the glass with lemonade have more quantity of coke mixed with it?

Solution:

This problem can be solved with algebra as well as logical reasoning. We are going to tell you how it is logically possible.
Be it any quantity that was present in the beginning and any liquid as well. We know that we have taken a spoonful from one glass and put it into another. Then, we have taken a spoonful from the other glass and put it into the first glass. So, at the end of it, the quantity of liquid in either glass remains same as it was in the beginning.

Therefore, we can conclude the fact that any amount of coke that is missing in the glass with coke will be present in the lemonade glass. Also, the same quantity of lemonade will be missing from the lemonade glass and will be present in the coke glass.

---

How could you solve humankind's biggest crisis given $1 billion and a spacecraft?
How would I explain the importance of HTML 5 to Larry Page and then to my grandma?
Let’s say you have to construct Google maps from scratch and guide a person standing on Gateway of India (Mumbai) to India Gate (Delhi). How do you do the same?
If you had access to a bank's database, how would you use that information to design an ATM for elderly people?
A man pushed his car to a hotel and lost his fortune. What happened?
What is your opinion on whether or not individuals should be required to use their official name when opening a Gmail or Google + account?
Tell me what you think about Google charging users $1 per month to use Gmail.
If you find all the above questions hard to answer, here comes the last one which will definitely give you a stroke even in understanding the question.

You’re the captain of a pirate ship, and your crew gets to vote on how the gold is divided up. If fewer than half of the pirates agree with you, you die. How do you recommend apportioning the gold in such a way that you get a good share of the booty, but still survive?

---

# Minimum cut Puzzle
You have got someone working for you for five days and a gold bar to pay him. You must give them a piece of gold at the end of every day. What are the fewest number of cuts to the bar of gold that will allow you to pay him 1/5th each day?

---

# 100 Doors
There are 100 doors in a row, all doors are initially closed. A person walks through all doors multiple times and toggle (if open then close, if close then open) them in the following way: In the first walk, the person toggles every door In the second walk, the person toggles every second door, i.e., 2nd, 4th, 6th, 8th, … In the third walk, the person toggles every third door, i.e. 3rd, 6th, 9th, … Likewise, In the 100th walk, the person toggles the 100th door. 
Which doors are open in the end?

Solution: 
A door is toggled in an ith walk if i divide door number. For example, door number 45 is toggled in the 1st, 3rd, 5th, 9th,15th, and 45th walks.
The door is switched back to an initial stage for every pair of divisors. For example, 45 is toggled 6 times for 3 pairs (5, 9), (15, 3), and (1, 45). 

It looks like all doors would become closed at the end. But there are door numbers that would open, for example, in 16, the divisors are (1,2,4,8,16) and as the pair(4,4) contributes only one divisor making the number of divisors odd, it would become open at the end. Similarly, all other perfect squares like 4, 9,…, and 100 would become open. Now, for prime numbers like 2,3,5,7… the divisors are (1, that number) and it is a pair, so they will remain closed at the end. And for all other numbers divisors are always in pairs, e.g. 15 = (1,15),(3,5), they will also remain closed.

So the answer is 1, 4, 9, 16, 25, 36, 49, 64, 81 and 100. 

---
 
# Find the fastest 3 horses
There are 25 horses among which you need to find out the fastest 3 horses. You can conduct a race among at most 5 to find out their relative speed. At no point, you can find out the actual speed of the horse in a race. Find out the minimum no. of races that are required to get the top 3 horses. 

Solution :
Make group of 5 horses and run 5 races. Suppose five groups are [a, b, c, d, e] and next alphabet is its individual rank in this group(of 5 horses).for eg. d3 means horse in group d and has rank 3rd in his group. [ 5 RACES DONE ] 
a1 b1 c1 d1 e1 
a2 b2 c2 d2 e2 
a3 b3 c3 d3 e3 
a4 b4 c4 d4 e4 
a5 b5 c5 d5 e5 

Now make a race of (a1,b1,c1,d1,e1).[RACE 6 DONE] suppose result is a1>b1>c1>d1>e1 
which implies a1 must be FIRST. 
b1 and c1 MAY BE(but not must be) 2nd and 3rd. 
FOR II position, horse will be either b1 or a2 
(we have to find top 3 horse therefore we choose horses b1,b2,a2,a3,c1 do racing among them [RACE 7 DONE]. 
The only possibilities are : 
c1 may be third 
b1 may be second or third 
b2 may be third 
a2 may be second or third 
a3 may be third 
The final result will give ANSWER. suppose result is a2>a3>b1>c1>b2 
then answer is a1,a2,a3,b1,c1. 
HENCE ANSWER is 7 RACES 

Please note that the 7 races work for the case also when all top 3 horses are same group or any top two horses are in same group. The group which has top 3 horses would always have winner in 6th race. In 7th race, we consider 2nd and 3rd horses of the group whose horse is overall winner. We also consider 2nd horse of the group whose horse came 2nd in 6th race. 

---

 
# Calculate total distance traveled by the bee
Two trains are on the same track and they are coming toward each other. The speed of the first train is 50 km/h and the speed of the second train is 70 km/h. A bee starts flying between the trains when the distance between two trains is 100 km. The bee first flies from the first train to the second train. Once it reaches the second train, it immediately flies back to the first train … and so on until trains collide. Calculate the total distance traveled by the bee. The speed of the bee is 80 km/h. 

Solution:

u = 50 km/hr
v = 70 km/hr
d = 100 km
b = 80 km/hr

Therefore, the total distance travelled by bee 
= b*d/(u+v) 
= 80 * 100/(50+70) 
= 66.67 km (approx)
---

# Birthday Cake Puzzle. 
3 cuts to cut the round cake into 8 equal pieces
You have a birthday cake and have to cut it into 8 equal pieces by making 3 cuts only. How do you do it?

<img src = "https://github.com/saurabhkaramankar/Readme_Collection/assets/70636541/0eead73f-229b-435f-a91b-3fc755150acd" width="300"/>
<img src = "https://github.com/saurabhkaramankar/Readme_Collection/assets/70636541/9b22d41d-bfd3-4c26-8b21-2f1b543af007" width="300"/>


---

 
# Find the last ball to remain after the entire process
There are 20 red balls and 16 blue balls in a bag. Any 2 balls are removed at each step and are replaced with a new ball on the basis of the following conditions: If they are of the same color, then they are replaced by a red ball. Once you take out the balls, you do not put them back in the bag – so the balls keep reducing. If they are of different colors, then they are replaced with a blue ball. Find the last ball to remain after the entire process.What is color of last ball
Here replacement means that the new ball is inserted into the bag.

Solution

Answer: Blue Balls

Observations:

There are basically 3 Cases:
1.When colors of both the picked balls are Red: Here, overall red balls are reduced by 2 and blue balls are increased by 1.
2.When colors of both the picked balls are Blue: Here, overall blue balls are decreased by 1.
3.When colors of both the picked balls are different: Here also, overall blue balls are decreased by 1.
Red Balls can only be reduced by two and that is in the 1st condition, i.e., if you choose both red balls, then they are replaced by a single blue ball, in no other ways you can reduce red balls. 
Blue Balls can be reduced by one in the  2nd  and 3rd condition if you choose both balls as blue and if both balls are of different color.
Now, since red balls are always reduced by two. So, at any point during the replacement process the count of red balls is always even, i.e. you will end up with either 0 or 2 or 4…(even number) red balls in the bag. There will never be a situation in which the bag contains an odd number of red balls. As a result, the last ball in the bag will be a blue ball in any combination of replacements.

---
 
# The Two Water Jug
You are on the side of the river. You are given an m liter jug and an n liter jug where 0 < m < n. Both the jugs are initially empty. The jugs don’t have markings to allow measuring smaller quantities. You have to use the jugs to measure d liters of water where d < n. Determine the minimum no of operations to be performed to obtain d liters of water in one of the jugs. 
The operations you can perform are: 
Empty a Jug
Fill a Jug
Pour water from one jug to the other until one of the jugs is either empty or full.

Solution:

<img src = "https://github.com/saurabhkaramankar/Readme_Collection/assets/70636541/3b0dd558-0a7e-48b1-aba0-1062839712eb" width="500"/>
For example, if we have a jug J1 of 5 liters (n = 5) and another jug J2 of 3 liters (m = 3) and we have to measure 1 liter of water using them. The associated equation will be 5n + 3m = 1. First of all this problem can be solved since gcd(3,5) = 1 which divides 1 (See this for detailed explanation). Using the Extended Euclid algorithm, we get values of n and m for which the equation is satisfied which are n = 2 and m = -3. These values of n, m also have some meaning like here n = 2 and m = -3 means that we have to fill J1 twice and empty J2 thrice. 
Now to find the minimum no of operations to be performed we have to decide which jug should be filled first. Depending upon which jug is chosen to be filled and which to be emptied we have two different solutions and the minimum among them would be our answer.

Solution 1 (Always pour from m liter jug into n liter jug) 

Fill the m litre jug and empty it into n liter jug.
Whenever the m liter jug becomes empty fill it.
Whenever the n liter jug becomes full empty it.
Repeat steps 1,2,3 till either n liter jug or the m liter jug contains d litres of water.
Each of steps 1, 2 and 3 are counted as one operation that we perform. Let us say algorithm 1 achieves the task in C1 no of operations.


Solution 2 (Always pour from n liter jug into m liter jug)  

Fill the n liter jug and empty it into m liter jug.
Whenever the n liter jug becomes empty fill it.
Whenever the m liter jug becomes full empty it.
Repeat steps 1, 2 and 3 till either n liter jug or the m liter jug contains d liters of water.
Let us say solution 2 achieves the task in C2 no of operations.
Now our final solution will be a minimum of C1 and C2.
Now we illustrate how both of the solutions work. Suppose there are a 3 liter jug and a 5 liter jug to measure 4 liters water so m = 3,n = 5 and d = 4. The associated Diophantine equation will be 3m + 5n = 4. We use pair (x, y) to represent amounts of water inside the 3-liter jug and 5-liter jug respectively in each pouring step.

/ Using Solution 1, successive pouring steps are: 

(0,0)->(3,0)->(0,3)->(3,3)->(1,5)->(1,0)->(0,1)->(3,1)->(0,4)
Hence the no of operations you need to perform are 8.

/ Using Solution 2, successive pouring steps are:  

(0,0)->(0,5)->(3,2)->(0,2)->(2,0)->(2,5)->(3,4)
Hence the no of operations you need to perform are 6.
Therefore, we would use solution 2 to measure 4 liters of water in 6 operations or moves. 

---
 
# 3 Bulbs and 3 Switches
There is a room with a door (closed) and three light bulbs. Outside the room, there are three switches, connected to the bulbs. You may manipulate the switches as you wish, but once you open the door you can’t change them. Identify each switch with its bulb. All bulbs are in working condition.

Solution:

Let the bulbs be X, Y, and Z 
Turn on switch X for 5 to 10 minutes. Turn it off and turn on switch Y. Open the door and touch the light bulb. 
1. the light is on from the bulb, it is Y 

Now we will check the other two off bulbs 
2. the bulb which is hot, is X 
3. the bulb which is cold, is Z  

---
 
# How to Measure 45 minutes using two identical wires?
How do we measure forty-five minutes using two identical wires, each of which takes an hour to burn? We have matchsticks with us. The wires burn non-uniformly. So, for example, the two halves of wire might burn in 10 minutes and 50 minutes respectively.

Solution

If we light a stick, it takes 60 minutes to burn completely. What if we light the stick from both sides? It will take exactly half the original time, i.e. 30 minutes to burn completely.

0 minutes – Light stick 1 on both sides and stick 2 on one side.

30 minutes – Stick 1 will be burnt out. Light the other end of stick 2.

45 minutes – Stick 2 will be burnt out. Thus 45 minutes is completely measured.

---

# 10 Balls in 5 Lines
Given are ten balls, the task is to place these 10 balls in five lines such that each line contains exactly 4 balls.

line contain exactly 4 balls.  Solution: The solution to the above puzzle can be obtained as:

Draw the star with a pentagon in the centre. 
Place each ball at the intersection of extended lines of pentagon 
Then place remaining balls on 5 vertices of pentagon. 
![Solution-_-10-Balls-in-5-Lines-Puzzle](https://github.com/saurabhkaramankar/Readme_Collection/assets/70636541/a4558651-c00e-4068-97ac-870df719ab38)


# Find ages of daughters
Alok has three daughters. His friend Shyam wants to know the ages of his daughters. Alok gives him the first hint.
The product of their ages is 72. 
Shyam says this is not enough information Alok gives him a second hint.
The sum of their ages is equal to my house number. 
Shyam goes out and looks at the house number and tells “I still do not have enough information to determine the ages”. 
Alok admits that Shyam can not guess and gives him the third hint
The oldest girl likes strawberry ice cream. 
Shyam is able to guess after the third hint.

---

 
# Pay an employee using a gold rod of 7 units?

An employee works for an employer for 7 days. The employer has a gold rod of 7 units. How does the employer pay to the employee, so that the number of employee’s rod units increases by one at the end of each day? The employer can make at most 2 cuts in the rod. 

(Hint- after the end of the day employee’s can’t spend any part of rod)

Solution: 
The employer can pay for seven days by making 2 cuts in a way that he has 3 rods of size 1, 2 and 4. 
1st Day: Employer gives 1 unit cut. 
2nd day: Takes back 1 unit cut from employee given on the first day and gives 2 unit cut. 
3rd Day: Gives 1 unit and then the employer is left with 4 unit rod lengths. 
4th Day: Takes back cuts of 1 and 2 units. Gives the cut of 4 units. 
5th Day: Gives cut of 1 unit to the employee. 
6th Day: Takes back cut of 1 unit and gives a cut of 2 units. 
7th Day: Gives cut of 1 unit to the employee. 

---
 
# Torch and Bridge
There are 4 people (A, B, C, and D) who want to cross a bridge at night.
A takes 1 minute to cross the bridge.
B takes 2 minutes to cross the bridge.
C takes 5 minutes to cross the bridge.
D takes 8 minutes to cross the bridge. 
          
---

# Poison and Rat
There are 1000 wine bottles. One of the bottles contains poisoned wine. A rat dies after one hour of drinking the poisoned wine. How many minimum rats are needed to figure out which bottle contains poison in hour. 

Solution: 
We need to figure out in hour. We need 10 rats to figure out the poisoned bottle. The result is based on binary number system. We get 10 using ⌈ Log21000 ⌉. 

The idea is to number bottles from 1 to 1000 and write their corresponding binary numbers on the bottle. Each rat is assigned a position in the binary numbers written on bottles. Let us take an example. Rat 1 represents first bit in every bottle, rat 2 represents second bit and so on. If rat numbers 2, 4 and 6 die, then bottle number 42 (Binary 0000101010) is poisoned. 


---

# Camel and Banana Puzzle
A person has 3000 bananas and a camel. The person wants to transport the maximum number of bananas to a destination which is 1000 KMs away, using only the camel as a mode of transportation. The camel cannot carry more than 1000 bananas at a time and eats a banana every km it travels. What is the maximum number of bananas that can be transferred to the destination using only camel (no other mode of transportation is allowed). 

---

# Bermuda Triangle
The Bermuda Triangle is a place in the Atlantic Ocean where ships and airplanes supposedly disappear without a trace. In the picture below, a square appears when we rearrange the pieces of the upper triangle to form the lower triangle. The pieces in both pictures are identical. Can you explain the origin of the square? You will need your knowledge of geometry to solve this problem. ![image](https://github.com/saurabhkaramankar/Readme_Collection/assets/70636541/2403593a-b260-49f7-96fa-2031a08cc592)
![image](https://github.com/saurabhkaramankar/Readme_Collection/assets/70636541/245c282e-6891-4412-9411-98763114718d) 

The area of a right triangle is computed by multiplying the base times the height and dividing by two. The pieces of the puzzle have an area of 32 square units. Although they can be assembled to form what appears to be a 13×5 right triangle, they actually form quadrilaterals that are slightly smaller or slightly bigger than a 13×5 right triangle. The long side of the these “triangles”, i.e, what seems to be the hypotenuse, is not a straight line.

The top figure has an area of 32 square units. The bottom figure, including the empty square, has an area of 33 square units. A real 13×5 right triangle would have an area of 32.5 square units. The distortion is difficult to see because one square of the picture is approximately 3% of the area.

The distortion can be seen more clearly when the empty square constitutes a larger percentage of the area, as in the figure below where 1 square represents 13% of the area.

---

# 9 min 2 hourglass puzzle.
Using only a Four-minute hourglass and a seven-minute hourglass,
How will you measure exactly nine minutes?

Restriction:- Without the process taking longer than nine minutes.

hourglass

Solution -
We measure 7 Minute from One Hourglass. We reverse it at 7th minute
And, 4+4=8 Minutes from Second Hourglass         –   8 Minutes
8(from 1)-7(From 2) = 1 Minute                                     –   1 Minutes
TOTAL = 9 MINUTES

EXPLANATION-
0 Minutes – Start both hourglass at the same time.
4 Minutes – The four minute glass runs out. Flip the four minute glass.
7 Minutes – The seven minute glass runs out. Flip the seven minute glass.
8 Minutes – The four minute glass runs out; the seven minute glass has been running for one minute. Flip the seven minute glass.
9 Minutes – The seven minute glass runs out.

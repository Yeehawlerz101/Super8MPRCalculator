# Super8MPRCalculator
##### Made by: Neil Master / Yeehawlerz101
### Simple summary:
A quick and easy way to not only calcualte your daily MPR's (minuets per room) but to also keep track of how you're doing.
This was made to not only help me with getting my MPR's done at the end of the day but also anyone else.
###### Please leave a "Star" or "Fork" this repo to let me know that you appreciate this project.
There will also be a url for the project that will be redirected to the github. I'll post it here: 
<a href="http://www.super8mprs.tk">http://www.super8mprs.tk</a>.
<hr>
### How the math is being done.
A = Start Time
B = Done/Out Time
C = Time Difference
Τ = Overall Time 
###### We take T and convert the hours into minuets.
D = Lunch Break Time Reduction
E = Completed Rooms
F = Completed Stay Overs
G = (E * 30)
H = (F * 15)
J = (G + H)
θ = MPR
1. Compare and find the time difference from A and B to get C. (A - B = C) 
2. By knowing how long we were punched out for lunch we can reduce C by that amount (As it's not a paid lunch). and Gives us T.
3. Take E and multiply it by 30 (30 Minuets per room). Giving us G.
4. Take F and multiply it by 15 (15 Minuets per stay over). Giving us H.
5. Take both G and H, then add them together giving us J.
6. Take J and now divide it by however many rooms were assigned (Rooms and stay overs) Giving us θ.
7. Then we simply round θ to the nearest whole number.
###### As a side note, we round the Total MPR value since it not only looks better but is easier to write.


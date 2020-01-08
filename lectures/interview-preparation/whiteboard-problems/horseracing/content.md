# Begin Solving
* 25 horses, 5 race-tracks with a max-capacity of 5 horses per race-track.
    * What is the minimum number of races to be ran to determine the top 3 fastest horses?







-
-
## Solution





-
-
## Part 1 
### Understanding the language

-
### Understanding the language
* To be as efficient as possible, we should begin racing as many horses as possible, utilizing as many race-tracks as possible.
* Fortunately, this math works out easily:
    * Divide the 25 horses into 5 groups of 5.
    * Race the horses in each group in a separate race-track





-
-
## Part 2
### Identify Knowns




-
### Identify Knowns
#### Race Tracks
* Assume racetracks are assigned a name
    * Racetack A
    * Racetack B
    * Racetack C
    * Racetack D
    * Racetack E





-
### Identify Knowns
#### Enumerating the Horses
* Assume each horse is respectively enumerated by their racetrack and placement.


-
### Identify Knowns
#### Enumerating the Horses
* For example (_truncated for brevity_):
    * Racetrack A:
        * `A1` is the fasted horse in Racetrack A
        * `A2` is the 2nd fasted horse in Racetrack A
        * ...
        * `A5` is the 5th fasted horse in Racetrack A
    * Racetrack B:
        * `B1` is the fasted horse in Racetrack B
        * `B2` is the 2nd fasted horse in Racetrack B
        * ...
        * `B5` is the 5th fasted horse in Racetrack B












-
-
### Part 3A
#### Induct Object Behaviors



-
#### Induct Racetrack Tiers
* Assume each racetrack is representative of a _tier_ of racer.
* Competitors in
    * `Race A` are generally faster than `Race B`
    * `Race B` are generally faster than `Race C`
    * `Race C` are generally faster than `Race D`
    * `Race D` are generally faster than `Race E`
    * `Race E` are generally faster than `Race F`




-
### Structuring Solution 
* Fortunately, this math works out easily:
    * Divide the 25 horses into 5 groups of 5.
    * Race the horses in each group in a separate race-track


-
#### Induct Winners
* 5 races are ran, thus 5 winners are found.
* We can assume `Race D` and `Race E` are amongst the slowest of horses
* We eliminate 10 horses and now are left with the top 15










-
-
### Part 3B
#### Deduct Object Behaviors


-
### Deduct Losers
* It follows that the 3 slowest horses of each of the five races can be ignored
    * Those with enumerations `4`, and `5` can be eliminated



-
-
#### Who are the Winners?
* Each winner is conclusively faster than the other 4 in their respective races.





-
### Step 2
* Race the winners found in step 1.
* The winner of this race is the fastest horse overall.



-
### Step 3


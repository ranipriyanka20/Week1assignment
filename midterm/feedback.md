# Midterm Feedback
The midterm feedback will be very similar to what you receive on a weekly basis for the homework, but more specific for each problem in this case.

## Final Score: 30/50


### Step 1: Priest Score Calculation
* **5pts** - Your code computed the correct probability and returned it
  * **Interesting way to write the code.  I'm not sure it's all working correctly.  (-1 pts) for missing probability on anything < 17**
* **(-2 pts) - No docstring**
* **(-3 pts) - No doctests**

**I'm confused by the second solution for the priest() score.  So, I just graded the first one**

### Step 2: Find a Hospital
* **5pts** - Your code correctly fetched the correct hospital given the inputs using requests
  * **(-4 pts) I don't see where your code actually uses that URL to retrieve the answer for which hospital to go to** 
* **2pts** - You had a docstring that described what the function was for
* **3pts** - You had at least three doctests in your docstring
  * **(-2 points) The code returns the URL, not th hospital name**

**But it looks like you have a solution for Step 2 in the spot for Step 3??**

**This one seems to work, so I'll add 4 points back on (+4 pts)**

### Step 3: Get the Hospital Address
* **5pts** - Your code correctly fetched the JSON file, parsed it, and looked up the hospital
  * **(-1 pts) I think you needed to handle convering hospital names to upper case**
* **(-2 pts) - No docstring**
* **(-3 pts) - No doctests**
* **(+5 pts) -- Updated 11/3 - it was confusing because you had this fucntion defined in two places.**

**Again, this code was in the wrong place.  It's very hard to grade something that's disorganized like this**

### Step 4: Process List of Patients
* **10pts** - Your code correctly fetched the psv file, looped through it, and ran your other functions
  * **(-2 pts) Something is misaligned in your output.  You have things like `'hospital': 'Unrestricted normal activity` which doesn't make sense**
  * **(-2 pts) The output format is not the data structure described**
* **2pts** - You had a docstring that described what the function was for

### Step 5: Compare Results
* **5pts** - Your code looped through all the results and compared them to the provided key
  * **(-2 pts) You had some good ideas, but `actual_data` never got populated in your notebook anywhere.**

### Extra Credit
* Up to 15 pts based on correctness and quality of the extra credit step

### Coding Best Practices:
**3 pts** - Was your code readable, efficient, and in line with what we learned in class?
* Good variable names?
* Code written into functions where appropriate?
* Appropriate comments with your code?
* Generally easy to follow and undersand?

**(-2 pts) Your midterm file was saved in the wrong place with the wrong name**

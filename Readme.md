# Anonymous Poll

Your university wants you to fill out an “anonymous” survey. There are many questions but some fields are mandatory:

* Gender
* Age
* Education
* Academic Year

Are you sure this is really anonymous? If you have a [list of all students](./resources/students) and you ask them to take a random survey, you may be able to identify the students who complete the survey.

The [list of students](./resources/students) is a text file. Each line has the information of a student in comma-separated values:

```
name1,gender1,age1,studies1,academic_year1
name2,gender2,age2,studies2,academic_year2
...
```
The gender can be “M” (male) or “F” (female).

## Input

Input starts with a number “T” (T <= 100) followed by “T” cases. Each case is a list of comma-separated values, which are:

```
gender,age,studies,academic_year
```

## Output

For each case, you must print the list of students that match the input. If there are multiple results, print them in lexicographical order and separated by commas. If there are not matches, print “NONE”.

Use the following format:

```
Case #Ti: Ri
```

Where “Ti” is the case number and “Ri” is the result.

## Implementation
- Implements the solution "Anonymous Poll" using **Object-Oriented Programming** and **SOLID principles** finding the best solution to create a maintainable software.

## Sample input

```
5
M,21,Human Resources Management,3
F,20,Systems Engineering,2
M,20,Manufacturing Engineering,3
M,18,Electrical Engineering,4
F,25,Construction Engineering,4
```

## Sample output

```
Case #1: NONE
Case #2: Morgan Martinez Moore
Case #3: Alfie Hernandez Diaz
Case #4: Mohammad Green Morales,Oliver Carter Rivera
Case #5: Ellie Brown Reed,Laura Stewart Foster,Nicole Peterson Torres
```

---
## ¿How to deliver the solution?
- When you finish, send an email attaching a zip with the solution to people@voxelgroup.net.
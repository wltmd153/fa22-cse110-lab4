1. 3, since variable defined for the whole function, it can be used outside of forloop 
2. 150, similarly, even though the variable was defined inside the loop, since it's var, its scope extends to the whole function so it can be accessed outside of loop
3. 150, self explanatory, since the variable was defined at the start of function, it can be accessed anywhere in the function.
4. [50,100,150], the discounted values were pushed inside the list for all of the iteration making this list.
5. i is not defined because it is only defined inside the forloop, so it causes an error
6. discountedPrice is not defined, it is only defined insdie the forloop, so it causes an error
7. Same reason with number 3, even though it was defined by let, since it was defined outside of any branch, inside the function, the variable can be used inside the function.
8. Let doesn't effect the list because all of the push happens inside the loop, and there aren't any "not defined" problem.
9. same reason with number 5, i is not defined outside of loop, since its scope is inside the forloop
10. 3, because const doesn't change and it was first initiated with prices's length which is 3
11. [50,100,150], even though the list is initiated with empty list, push doesn't reinitiate or redefine the variable, it just pushed value inside the list, which doesn't have to do with const
12. 
a. student.name
b. student['Grad Year']
c. student.greeting()
d. student['Favorite Teacher'].name
e. student.courseLoad[0]
13.
a.32
b.1
c.3
d.3null
e.4
f.0
g.3undefined
h.NaN
14.
a. true
b. false
c. true
d. false
e. false
f. true
15. == is just equal and === is strictly equal. strictly equal means that the values have to be exactly equal, which means 2 === '2' is not equal.
16. for(let property in student){
        
        if(property[0] == 'r')
            console.log(property);
        else if(student[property] % 2 == 1)
            console.log(property);
        
    }
17. first, the function and the array is passed down, inside the function modifyArray, newArr is defined and for loop begins, for each forloops, the function is called
for all of the values in the array and all the values are doubled, pushed on to the newArr. result is [2,4,6]

18. var intervalId = setInterval(function(){
  let d = new Date();
  let time = d.toLocaleTimeString();
  console.log(time);
}, 1000);
19. 1 4 3 2
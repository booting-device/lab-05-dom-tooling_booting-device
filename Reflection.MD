# Why synchronizing the DOM by hand is tedius

Synchronizing the DOM by hand is tedoious because It's a 2-step problem
- Find the desired parent element, through a class or id or iteration. Requires the target parent element to have an id or class or face inefficient iteration. 
- Create a new element through JS object oriented HTML element system. All fields, classes and ids need to be assigned in different lines / expressions.
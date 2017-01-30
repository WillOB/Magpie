#Answers
##Exploration: Using the API
If the substring does not occur, IndexOf() returns -1.

##Exploration: Understand the new method
findKeyword("She's my sister", "sister", 0);
iteration 1 psn: 9 before: " " after: " "

findKeyword("Brother Tom is helpful", "brother", 0);
iteration: 1 psn: 0 before: after: " "

findKeyword("I can't catch wild cats.", "cat", 0);
iteration: 1 psn: 8 before: " " after: "c"
iteration: 2 psn: 16 before: " " after: "c"

findKeyword("I know nothing about snow plows.", "no", 0);
iteration: 1 psn: 3 before: "k" after: "w"
iteration: 2 psn: 7 before: " " after: "t"
iteration: 3 psn: 22 before: "s" after: "w"

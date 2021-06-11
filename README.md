entering 0 should result in "0"
entering 1 results in "Beep!"
entering 2 results in "Boop!"
entering 3 results in "Won't you be my neighbor?"
Any other numbers should return those numbers
Any entry that is not a number should return "Does not compute!"
Any number that includes 1, 2, or three should return the above response in descending order (ie, any number with a 3 in it returns "Won't you be my neighbor?")

Describe: beepBoop()
Test: "It should return an array of 0 if the number 0 is inputted"
Expect: beepBoop(0).toEqual([0]);
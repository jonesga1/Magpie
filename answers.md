What value is returned by indexOf if the substring does not occur in the string?

Returns -1 if not found.


findKeyword("She's my sister", "sister", 0); 
Position: 8, Before: "", After "",
findKeyword("Brother Tom is helpful", "brother", 0); 
Postion: 0; Before: "", After "",
findKeyword("I can't catch wild cats.", "cat", 0); 
Position: 8; Before: "", After "c",
Position: 19; Before "", After "s",
findKeyword("I know nothing about snow plows.", "no", 0);
Position: 3; Before: "k", After: "w",
Position: 7; Before: "", After "t",
Position: 22; Before: "s", After "w",

# AD311-Tech-Interview-Prep-TextWise-Solutions-Recursion
Tech Interview Prep: TextWise Solutions | Recursion


William Anderson

AD311

The string reversal function must be implemented using recursion to demonstrate the engineering team's ability to apply fundamental computer science principles in developing practical solutions.

A base case must be used for the stack to prevented infinite looping.


START
   ↓
Call reverseString("hello")
   ↓
Is string empty or length 1?
   ↓
   NO
   ↓
Call reverseString("ello") + "h"
   ↓
(Recursion continues...)
   ↓
Base Case reached ("o")
   ↓
Build string backwards
   ↓
Return "olleh"
   ↓
Print to console
   ↓
END

Normal test case will test 3 different strings: "hello", "textwise", "12345". 
Test edge will test empty quotes " ", " ", " ", 




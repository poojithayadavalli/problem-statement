# problem-statement #Stack

Ram has a disability of reading text in reverse order.He found a paper which was torn into pieces.He wants to read the content in that paper.
So he found all pieces of paper and read the content in each piece in reverse order because of his disability.So he is asking for your help. 
You are given a string s that consists of English letters and brackets.The string in the brackets represent the content of each piece of paper 
which is read by Ram.Reverse the strings in each pair of matching parentheses, starting from the innermost one.
Your result should not contain any brackets.

Constraints:

0 <= s.length <= 2000
s only contains English characters and parentheses.
It's guaranteed that all parentheses are balanced.

Example:

Input:"(mo(ivug)rf)"                                                                                                                      
Output: "fromguvi"
Explanation: The substring "guvi" is reversed first, then the whole string is reversed.


Testcases:

Case 1:

Input: s = "(abcd)"

Output: "dcba"

Case 2:

 Input: s = "(iv(morf)ug)" 
 
Output: "fromguvi"

Case 3:

Input: s = "(gni(rts(ol))gn)"

Output: "longstring"

Case 4:

Input: s = "a(bcdefghijkl(mno)p)q"

Output: "apmnolkjihgfedcbq"

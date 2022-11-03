#######################################################################################################################################################################
# my_DSA_cheat_Sheet

* Two Pointers(Neetcode)

EASY ----------------------------------------------------------------------------------------------------------------------------------------------------------

1-Remove Duplicates from Sorted Array ---> O(1) me krna h islie , do pointer lelo left and ryt =1;  ryt wale ko 1 se chala kr pure arr pr chalao , jaha jaha usko left index pr pdi value ryt index se alag mile , arr[left]=arr[ryt] aise update krte chalo and return the left ;0

2-Move Zeroes--->  2 pointer lelo left , ryt =0; ryt ko pure loop pr chalao ,  jaise hi arr[ryt]!=0 aaye , swap it with arr[left] and left ++;

3-Valid Palindrome--->  s=   s.toLowerCase();  s=s.replaceAll("[^a-zA-Z0-9]",""); ye do se wo single string bn jayega ab isko while se check kr lo palin hai ki nahi .

4-Valid Palindrome 2 ---> ek check palin fn bnao simple fn(str,i,j) ye pointer bhi lega , ab pure string pr two pointer lagao jse hi str[i]!=str[j] aaye uske bd recursion se dono condition check kr lo -- by this cammand    {return checkPalin(s,x+1,y)||checkPalin(s,x,y-1);} ek bo true to true wrna false; kahani khtm

5-Minimum Difference Between Highest and Lowest of K Scores--->sort kr lo phle, ab sliding window laga kr check kro highest lowest ka diff min kro aur brute lagao easy h question sahi se pdhna bs

6-Reverse String---> kuch nahi bs do pointer lelo , i =0; j = arr.length; swap kr do while loop chala kr

7-Merge Sorted Array--->



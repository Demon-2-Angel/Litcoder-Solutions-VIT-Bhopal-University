<h1>Maximize Subsequences in String</h1>
You are given two strings, **text** and **pattern**, both consisting of only lowercase English letters.
<br>

The objective is to modify the text by adding either `pattern[0]` or `pattern[1]` exactly once at any position. 
After the modification, you need to determine the maximum number of times the pattern can occur as a subsequence in the modified text.
A subsequence is a sequence of characters obtained by deleting some or no characters from the original sequence without changing the order of the remaining characters.
<br>

Example with Explanation<br>
Input text is `“abdcdbc”.` Input Pattern is `“ac”`. <br>
When inserting `'a'` as Pattern [0] between text [1] and text [2], the resulting string is "abadcdbc."
<br>
<br>
After deleting `“bd”` in the newly created text, we will get “aacc”. In this modified string, the subsequence "ac" appears four times. <br>

Some other combinations are,
1.  aabdcdbc -> aacc -> Four times<br>
2.  abdacdbc -> aacc-> Four times<br>
3.  abdcadbc -> acac -> Three times<br>
4.  abdccdbc -> accc -> Three times<br>
5.  abdcdbcc -> accc -> Three times<br>

<br>
<br>

Input and Output format:
<br>
Exercise-1
<br>
Input: 

`
ababc` <br>
`
ab
`
<br>
<br>
Output:
`
5
`

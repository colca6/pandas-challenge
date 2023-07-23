# pandas-challenge
Module 4 homework
README

Mod 4 homework I found a little bit easier than Mod 3.  I was able to find most everything in an exercise that we covered in class.  However, it still took me a good 8-10 hours of solid work.  This was because even though I could find examples for dataframes, groupby, etc, they still often times didn't work. Mostly due to syntax, single or double quotes, missing parentheses, brackets, etc.  I still don't have a logic to know when to use which brackets or quotes, etc.

Also, we worked this assignment in Jupyter notebook, which of course, is new to me. While the concept is really nice, and it is great to run snippets, instead of huge chunks of code, it also made it very difficult to keep things straight, like names of many similar but different dataframes and variables.  Perhaps I could have developed a better system, but maybe next time.

Another Jupyter problem I had was being sure something "above" didn't prevent current code from working. This happened a few times. Most notably, when trying to execute the code for binned spending per student amounts, for mean of math or reading scores, even though this code was provided.  It wouldn't run, and I was stuck here for well over an hour.

BCS Assistance to the rescue again.  "dchau" helped me by finding that code "above" had created the dataframe I was working with, to have an empty row, somehow. I now see that it was because I did "set_index" on 2 columns, not realizing that the first set would mess up the second.  We changed that code to a groupby, and also eliminated formatting of the output, because adding the "$" in formatting was causing Jupyter (or pandas, or python) to see it as string, not a number, and can't do the mean on it.

This homework was LOOOOOONG!  It seemed never-ending.  After finishing, however, I can see the structure of it all, and that was informative.  For example, get school budget. Then calculations, math scores, reading scores, passing, overall.  Then repeat that for school type.  Then bin spending per student, repeat same or similar calculations, and in each case, create dataframe to show this data summarized.  So I could see the workflow.  But man was it long!
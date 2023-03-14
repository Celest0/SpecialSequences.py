# SpecialSequences.py
You are a social media marketing specialist doing research on social networks.
Write a program for your research that will take text as input and output all of the hashtags in it separately.

Sample Input
No #pressure, no #diamonds

Sample Output
#pressure
#diamonds


import re
text = input()
#your code goes here
#use re.findall() with r"#\w+" as the regex


match= re.findall(r"#\w+", text)
if match:
     print("\n".join(match) )

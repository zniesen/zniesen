import string

#creating sample string
sample_string = "Have you ever been to the water spout? to the very bottom of the water system. There you'll find a little Aligator who goes by the name of Alfred. If you do, he's mine. I lost him. I threw him down the water spout, and, now, I'm feeling lonely cause he's gone. I miss him."

#making string lowercase and removing all punctuation
lc_string = sample_string.translate(str.maketrans('', '', string.punctuation)).lower()

#splitting the string into a list of words
res = lc_string.split()

#creating empty arrays for all words and how many times each word is used
words = []
counter = []

#filling words array with all unique words from string and filling counter array accordingly
for i in res:
  if i in words:
    continue
  else:
    words.append(i)
    counter.append(res.count(i)) #updating counter for word

#printing result
print (words)
print (counter)
     

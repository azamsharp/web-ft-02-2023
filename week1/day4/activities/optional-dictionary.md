Dictionary Exercises
Exercise 1
Given the following dictionary, representing a mapping from names to phone numbers:

`
phonebook_dict = {
  'Alice': '703-493-1834',
  'Bob': '857-384-1234',
  'Elizabeth': '484-584-2923'
}
`

Write code to do the following:

Print Elizabeth's phone number.
Add an entry to the dictionary: Kareem's number is 938-489-1234.
Delete Alice's phone entry.
Change Bob's phone number to '968-345-2345'.
Print all the phone entries.
In this exercise, are you using dynamic keys or fixed keys?

Exercise 2: Nested Dictionaries

`
ramit = {
  'name': 'Ramit',
  'email': 'ramit@gmail.com',
  'interests': ['movies', 'tennis'],
  'friends': [
    {
      'name': 'Jasmine',
      'email': 'jasmine@yahoo.com',
      'interests': ['photography', 'tennis']
    },
    {
      'name': 'Jan',
      'email': 'jan@hotmail.com',
      'interests': ['movies', 'tv']
    }
  ]
}`

Write a python expression that gets the email address of Ramit.
Write a python expression that gets the first of Ramit's interests.
Write a python expression that gets the email address of Jasmine.
Write a python expression that gets the second of Jan's two interests.
In this exercise, are you using dynamic keys or fixed keys?

Letter Summary
Write a letter_histogram program that asks the user for input, and prints a dictionary containing the tally of how many times each letter in the alphabet was used in the word. For example:

$ python letter_histogram.py
Please enter a word: banana
{'a': 3, 'b': 1, 'n': 2}
In this exercise, are you using dynamic keys or fixed keys?

Word Summary
Write a word_histogram program that asks the user for a sentence as its input, and prints a dictionary containing the tally of how many times each word in the alphabet was used in the text. For example:

$ python word_histogram.py
Please enter a sentence: To be or not to be
{'to': 2, 'be': 2, 'or': 1, 'not': 1}
In this exercise, are you using dynamic keys or fixed keys?

Bonus Challenge
Given a histogram tally (one returned from either letter_histogram or word_summary), print the top 3 words or letters.

$ python word_histogram_tally.py

Please enter a sentence: To be or not to be do be do be do
The top three words are:
be: 4
do: 3
to: 2
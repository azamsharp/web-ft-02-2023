### Array Chunking
Write a function that takes two inputs, an array and a size. Break the array into chunks of the given size. For example, if given an array of [8,9,2,435,42] and a size of 2, your function would return [[8,9], [2,435], [42]]. 
#### Array Chunking 1.5 
Adjust your function so that it takes three inputs, and returns not just a size but a position. So if your array was [8,93,532,42,1,2] with size 3 and position 2, we would return [42,1,2] - the second chunk of 3.

### Caesar Shift
You're a nerdy high school boy looking to ask his equally nerdy partner to prom. Since you're both cryptography nerds, you figure it would be particularly cute to encode the message you send him, but you don't want to make the code too hard to break. You decide on a simple Caesar shift; you'll pick a number, then shift every letter in your note forward in the alphabet by that number. For example, starting with LOVE and 4, you know that P is the 4th letter after L (M, N, O, P), S is the 4th letter after O (P Q R S), Z is the 4th letter after V (W X Y Z) and I is the 4th letter after E (F G H I), so your output would be PSZV.
##### Hint: You'll want to use an array for the entire alphabet somewhere along the line.

#### Caesar Unshift
You're a nerdy high schooler whose equally nerdy boyfriend just asked them to prom. You think? The entire message is encoded,a nd it looks like your erstwhile boyfriend decided to give you a range of shift possibilities, instead of actually telling you the cipher key. You know, for example, that the message he sent you is PSZV, but he decided to tell you that the shift range was 4-6 - maybe he's shifted the letters forward by  4, but maybe he's shifted them forward by 5 or 6 instead. Create a function that deciphers all potential messages within the range.
##### Bonus: You know your boyfriend calls you BOO all the time, and that that sequence will (probably) be in any messages you decipher correctly. Add an extra condition to your shift function wherein if the phrase BOO appears in your decoded message, it gives you only that message (which is probably correct) versus all translations in range.

#### Button Bash
Your client wants buttons to-order. They want to be able to enter a color on your website and have a button of the corresponding color pop up. Adjust your methods so that the client would be able to ask for colors like 'blue', 'BLUE', and 'Blue' without errors, and so that if the client tries something your CSS can't adjust to immediately - like 'argent' instead of silver - a modal message tells the client that their color preference isn't available.
##### Bonus: Instead of just telling your client no when they implement a color name your CSS doesn't understand, try offering them the ability to input the color in RGB or Hex. 

#### Finding Typos
You, geeky mama, want to test your three-year-old's typing capacity using a computer program. You created a dictionary with keys of words you expect your little one to be able to type, like 'porpoise' or 'gratuity'. The definitions you left blank for your kid to input; the first step of this program should be asking the user to input the spelling of each of the keys in the proper place. So, you create a dictionary of {'dolphin': ''} or {'dolphin': null}, and the program should output a message asking for user input to type out 'dolphin'. 

After your child has typed all the words out, check if their typing matches yours. Maybe you typed {'dolphin'} for your key, but your child typed {'doplhin'} for the definition - incorrect, and it should return false.
##### Bonus: 'Dolphin' and 'Doplhin' aren't the same, but they do have the same component letters. Check for where your kid misspelled versus typed the word wrong.

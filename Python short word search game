word_list = ["ardvark", "baboon", "camel"]

import random #imports the random function 

chosen_word = random.choice(word_list)#random.choice - chooses a random element from whatevers is in the ()


print("Hidden Word: {" + chosen_word + "}")

display = []#list
for count in chosen_word:#for as many letters they are in the chosen_word
  display += "_"#replace them with _
print(display)

end_of_game = False

while not end_of_game:
  guess = input("Guess a letter: ").lower()#lower() - uncapitalizes letters in a word store user letter input in a variable called guess
  for position in range(len(chosen_word)):
  #loops inside the word, looking at every letter
    letter = chosen_word[position]#checks if guessletter is = to letter in word
    if letter == guess:#if letter matches the guessedword
      display[position] = letter#position of letter is replaces with guessletter
  print(display)

  if "_" not in display:
    end_of_game = True
    print("You win")
  

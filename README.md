# Algorithm-checkpoint

Gomycode checkpoint Algorithm Project using the algo vscode extention

ALGORITHM THAT READS THE NUMBERS OF CHARACTERS, NUM OF WORDS AND NUMBERS OF VOWELS SOUNDS  IN THE SENTENCE

#EXPLANATION OF THE CODE

Line 4: Element checking is the algorithm name and its the first line of the code
Line 5-7 Declaration of 3 variable as counter and give them integer as data type
       char_counter, Word_counter and Vowel_counter  
Line 8 :Declaration of another variable sentence and give it a string data type
Line 13- while the sentence length 'i' , DO the followings:
Line 14 -20 check (It gives us the number of space and number of character in the sentence )
   i. if the sentence has a space, then space counter equals space counter plus ONE
   else  counter equals Charcter counter plus ONE
   end the "if" condition
   Line 23-30 Gives us the number of vowel sounds in the sentence
   The vowel sounds are a, e,i,o,u.
   At every loop (case),once there is VOWEL soundin the sentence, the vowel_counter will add one.
   we add the BREAK keyword so the sentence is checked for all the vowel sounds from the begining again after meeting a true condition. (looping from the first case again until the end of the last character in the sentence.
   Line 32 enables us to check the characters one after the other for all the vowels in every single loop
   Line 35 Give us the word_counter value by adding the ONE to the space_counter value

   Line 39-41 This write the values for character counter, word counter and vowel counter.
   Line 43 End of the algorithm
   



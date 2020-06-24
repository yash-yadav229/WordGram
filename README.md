# WordGram
WordGram is a Java project which creates random text based on a training text. In brief ,  it picks up a few words (key) randomly and then searches for the words that follow the key it choose randomly. Out the those bundle of words it chooses next word randomly considering the increased probability of the words which come after the key more often. Then the first word is removed from the key and the new word chosen is added to the end creating the next key, and it goes on. As I said it is a brief explanation. The complexity can be understood by taking a look at the code. For example, I had to create a different WordGram class and general methods that a "String" has due to a few limitations of the String class.

P.S. : 1. To run this code you'll need to clone the repository along with the libraries and the data files.
       2. It uses a custom edu.duke library for using FilesResource and DirectoryResource classes to take input from files.
       3. You will have to select all the files from the dictionary folder when the dialouge box appears.(will fix this too)
       4. By default the file with coded message is "athens.txt".
       5. You can check the coded msg by checking the above mentioned file.
       6. The output for decoded message in different messages will be visible in the console of your IDE.
       

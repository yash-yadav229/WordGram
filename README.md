# WordGram
WordGram is a Java project which creates random text based on a training text. In brief ,  it picks up a few words (key) randomly and then searches for the words that follow the key it choose randomly. Out the those bundle of words it chooses next word randomly considering the increased probability of the words which come after the key more often. Then the first word is removed from the key and the new word chosen is added to the end creating the next key, and it goes on. As I said it is a brief explanation. The complexity can be understood by taking a look at the code. For example, I had to create a different WordGram class and general methods that a "String" has due to a few limitations of the String class.


       

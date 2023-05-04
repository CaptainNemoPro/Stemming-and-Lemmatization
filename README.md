# Stemming-and-Lemmatization

![alt text](https://s3-ap-south-1.amazonaws.com/av-blog-media/wp-content/uploads/2019/07/Screenshot-from-2019-07-18-12-31-12.png)

# What is Stemming?

Stemming is the process of getting different morphological variations given a root word.

# What is Lemmatizing?

Lemmatization involves transforming plural words into singular form. Its primary objective is to decrease the number of distinct words during vectorization. By lemmatizing, the vectorizer can treat "horse" and "horses" as identical terms, resulting in a reduction of the unique word count.

# What has been executed/accomplished?

The file contains a Python function designed to receive a string or sentence as input and produce a lemmatized version of the sentence as output. The purpose of creating such a function is to simplify the lemmatization process, which is applied only to words, not sentences. Without this function, we would need to perform the lemmatization task word by word for a given sentence, whereas this function performs the task in the background and returns the desired result.

Steps in the function.

![alt text](https://4.bp.blogspot.com/-o-EoNKsW6c8/WLmQG4cG_WI/AAAAAAAAAUA/eiGMcM8R70AzhPsrl6VO344gTt1MKStGwCLcB/s1600/Stairs.gif)

1. The sentence was tokenized into individual words.
2. An empty list was initialized for the purpose of adding lemmatized words.
3. A for loop was established to iterate through each word and perform lemmatization.
4. Each word was added to the list after being lemmatized.
5. The resulting list of lemmatized words was returned.

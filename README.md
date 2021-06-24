
#                  `Build a language model by using statistical technique`


## Steps to follow:

### 📍📍 1.**`Read the Text file`**  
   - **-  Here we read the Text file as in the form of paragraphs**
   - If we want to change the text file, then just change the path location of the needed text file
   - NOTE: Text file should be in the form of paragraphs. If it would be in the sentence form then there is a no need of sentensification code block in this code.
 
### 📍📍 2.**`Pre-Processing Text data`**
   - **-  Clean the data using regular expressions**
   - **-  Sentencification**
   - **-  Spliting the data into Train,Test and Valid**
   - **-  Creating Unigrams,Bigrams and Trigrams For given sentences**
   - **-  Finding Unigrams,Bigrams and Trigrams Counts for Test Set**
  
### 📍📍 3.**`Applying Smoothing Techniques on tri-grams`**
   - **-  Maximum Likelyhood estimation**
          For this we required count of the n-grams
   - **-  Add-one Smoothing**
          For this we required count of the n-grams and also Unique Vocabulary size of the N-grams
   - **-  Add-k Smoothing**
          For this we required count of the n-grams and also Unique Vocabulary size of the N-grams and also choos the K value
   - **-  Good Turing Smoothing**
          For this we required the count of frequencies of N-grams    
   - **-  Kneyserney Smoothing**
          Need to create a function for finding "given word" similar n-grams, function for finding "Predicted word" similar 
          n-grams and count of the n-grams and also Unique Vocabulary size and Total Vocabulary size of the N-grams          
   - **-  Written Bell Smoothing**   
          Need to create a function for caliculating more than one frequency counts

### 📍📍 4.**`Perplexity Caliculation on all 5 smoothing techniques`**
 #### Final Results:
 ![Final Output: Perplexity scores](https://github.com/Kranthi596rguktian/Statistical-Language-Model/blob/main/Final%20Perplexity%20scores.png)

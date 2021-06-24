# Steps To Follow
#### 1.Read the Text File

       Read Telugu_data_v2.txt file

   



#### 2.Preprocessing on Text Data

         Here we find the challenges and we tokenized the data using regular  
         expressions.

         sentencification
    
         Next divided the data into train,test and valid.

         Divided data into unigram,bigram,trigram upto ngrams.
    
         calulate the frequencies of unigram,bigram upto ngrams of train data.

#### 3.Applying Smoothing Techniques on Test data.

     a)Laplace smoothing:
        
          In this we required count of ngrams and n-1 grams and number of unique
          words.
        
     b)Additive Smoothing:
    
         In this we required ngram,n-1 gram counts,unique words and k-value.
        
     c)Good Turing Smoothing:
    
         we need frequency of frequencies of ngrams.
        
     d)Kneyser-ney Smoothing:
    
         predicting the next word using the frequencies of previous words and
         continuation words.
    
     e)Witten-bell Smoothing:
    
         create a function for calculating more than 1 frequency counts
        
#### 4)Applying neural language model on train,test and valid data.
     
      

# How To Execute

#### 1) For Preprocessing 

          Run challenges.ipynb
          
             output:tokens
          Run libraries.ipynb
            output: tokens (based on different inbuilt libraries)
             
        if you want to add more challenges means you can add in challenges one.
        
#### 2)For Language modelling 

         run ngrams.ipynb
         
                 output: perplexity scores and probabilities of all smoothing
                         techniques. 
                         
#### 3)For Neural language model 

         run -python model.py <filepath>
         
               output: perplexity scores
    

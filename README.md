# Learning Pytorch
Going through the Pytorch tutorials and other material. Using the tutorials as a way to play with the code and understand it thoroughly. 

### LSTM tutorial
After completing the LSTM tutorial, I decided to then work on my own LSTM to create lyrics for songs. 
So I got the lyrics for **Dr. Seuss – "Green Eggs And Ham"**, and trained the model paragraph by paragraph.

Input data formatted like:

```[['I', 'am', 'Daniel', '\n', 'I', 'am', 'Sam', '\n', 'Sam', 'I', 'am', '\n'], ['That', 'Sam-I-am', '\n', ...]```

The following is the resulting generations after 200 epochs, without shuffling, and compared to the original lyrics, it appears to be somewhat new.

```Sam ! 
 If you will let me be , 
 I will try them . 
 You will see . 
 Sam Sam ! 
 Sam ! 
 I would not , could not , in a boat . 
 Not in the dark ! 
 Not in a car ! Not in a tree ! 
 I do not like them , Sam , you see . 
 Not in a house . Not in a box . 
 Not with a mouse . Not with a fox . 
 I will not eat them here or there . 
 I do not like them anywhere ! 
 I do not like green eggs and ham . 
 I do not like them , Sam-I-am . 
 I do not like green eggs and ham . 
 I do not like them , Sam-I-am . 
 I do not like green eggs and ham . 
 I do not like them , Sam-I-am . 
 I do not like green eggs and ham . 
 I do not like them , Sam-I-am . 
 I do not like green eggs and ham . 
 I do not like them 
 ```

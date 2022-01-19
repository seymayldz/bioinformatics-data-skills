# bioinformatics-data-skills

## A1.1. 
First of all, I called two libraries. *numpy and seaborn*.
The codes I used for that:     
```
import numpy as np
import seaborn as sns
```
I created a numpy array of random integers. I set a size for it (100X100 matrix). This index of integers ranges from [0, 100].
The code I used for that:
```
array= np.random.randint(0,101, size=(100,100))
```
I named this array I created "array". And I included 100. The code also passes 'int' to be integers.
To run the code I typed ```array``` and run the code.
There are dots in between because I chose a very long string of numbers. But I can see a few of them here. For the output [Final MBG6133- Şeyma Yıldız](https://github.com/seymayldz/bioinformatics-data-skills/blob/9ac366576abdc8fa49000b269de82be689f7bde4/Final%20MBG6133-%20%C5%9Eeyma%20YILDIZ.ipynb) you can go to out[4].

## A1.2.

I created a heatmap for the array I created earlier. The code I use to do this:
```
sns.heatmap(array)
```
When I ran this code, *< axessubplot :>* text appeared on the headmap. I used one more code to delete this post. Code: 
```
plt.show()
```
I had to call another library to show the headmap I created with "poster" code. The code I use for this is: 
```
import matplotlib.pylab as plt
```
Here is the code I used to make a poster after calling this library: 
```
sns.set_context("poster")
```
For the output [Final MBG6133- Şeyma Yıldız](https://github.com/seymayldz/bioinformatics-data-skills/blob/9ac366576abdc8fa49000b269de82be689f7bde4/Final%20MBG6133-%20%C5%9Eeyma%20YILDIZ.ipynb) you can go to In[5]. 

## A2.1. 

I wanted to separate the odd numbers from the numbers in the array I created with the ```array %2!=0``` code. With the code here, I said "do not get 0 when the numbers in the array are divided by 2". "!" used to negate the sign. For the output [Final MBG6133- Şeyma Yıldız](https://github.com/seymayldz/bioinformatics-data-skills/blob/9ac366576abdc8fa49000b269de82be689f7bde4/Final%20MBG6133-%20%C5%9Eeyma%20YILDIZ.ipynb) you can go to Out[6]. 
The output here is true, false. I wanted to change it to [0,1]. The code I used for that: 
```
new_array.astype(int)
``` 
0 means false in python. 1 means correct.I gave a new name to the array I created with this code I used. *new_array.*  
```
.astype(int)
``` 
This command can also be used to transform vectors, matrices and columns in an array. However, int() is a Python function that can only be applied to scalar values. For the output [Final MBG6133- Şeyma Yıldız](https://github.com/seymayldz/bioinformatics-data-skills/blob/9ac366576abdc8fa49000b269de82be689f7bde4/Final%20MBG6133-%20%C5%9Eeyma%20YILDIZ.ipynb) you can go to Out[9]. 

## A2.2. 

As in A1.2, I created a heatmap here as well. I created a new array in A2.1. It's name was *new_array*. I created a heatmap for it. Here I used the code ```new_array.astype(int)``` that I used before, inside the ```sns.heatmap()``` command. The code was like this: 
```
sns.heatmap(new_array.astype(int))
``` 
When I ran this code, *< axessubplot :>* text appeared on the heatmap. I used one more code to delete this post. Code: 
```
plt.show()
``` 
I had previously called a library to show the heatmap I created with the "poster" code. I don't need to call again. I've made it a poster here again. 
```
sns.set_context("poster")
``` 
I used your code.  For the output [Final MBG6133- Şeyma Yıldız](https://github.com/seymayldz/bioinformatics-data-skills/blob/9ac366576abdc8fa49000b269de82be689f7bde4/Final%20MBG6133-%20%C5%9Eeyma%20YILDIZ.ipynb) you can go to In[14]. 




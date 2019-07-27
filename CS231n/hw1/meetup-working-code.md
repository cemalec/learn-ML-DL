# Meetup Links to Working Code, Stanford cs231n Assignment 1  


### Chris Malec:

   Two layer nn:
   https://github.com/cemalec/CS231/blob/master/assignment1/  
  
   knn, svm:  
   https://github.com/cemalec/CS231/blob/master/assignment1/knn.ipynb  
   https://github.com/cemalec/CS231/blob/master/assignment1/cs231n/classifiers/neural_net.py
   
   https://github.com/cemalec/CS231/blob/master/assignment1/svm.ipynb  
   https://github.com/cemalec/CS231/blob/master/assignment1/softmax.ipynb  
   https://github.com/cemalec/CS231/blob/master/assignment1/two_layer_net.ipynb  
   
   Math for svm, softmax, Back Prop: https://cemalec.github.io/main/    
   https://cemalec.github.io/Gradients_Softmax/  
   https://cemalec.github.io/Gradients_Hingeloss/  
   ttps://cemalec.github.io/Gradients_NN/ (edited)   
   
   
### Colleen Chen: 

https://github.com/colleen-chen/learn--cs231n-

 - Two layer nn:  
   https://github.com/colleen-chen/learn--cs231n-/blob/master/two_layer_net.ipynb  
   https://github.com/colleen-chen/learn--cs231n-/blob/master/classifier/neural_net.py  
   
 - knn and softmax:  
   https://github.com/colleen-chen/learn--cs231n-/blob/master/knn.ipynb  
   https://github.com/colleen-chen/learn--cs231n-/blob/master/classifier/k_nearest_neighbor.py  
   https://github.com/colleen-chen/learn--cs231n-/blob/master/softmax.ipynb  
   https://github.com/colleen-chen/learn--cs231n-/blob/master/classifier/softmax.py  
   
   
### Nathan Bendich:     

   https://www.dropbox.com/s/llgiwyqril6ljms/cs231n_assn1___working_2-deep_NN.tar.xz?dl=0 . 
   You can probably just "double-click" on the file name too and something will pop up to decompress it.  Please let me know if you have any questions.  I can try to explain as best as possible while I'm not working on the next part of the assignment.   
   >tar -xvf cs231n_assn1___working_2-deep_NN.tar.xz  (to unzip)  
   

### Peter -- to add

   softmax code part of codeshare file: 
   [a relative link](codeshare_hw1b.py)

>      Markdown: relative link help:
>      [a link](https://github.com/user/repo/blob/branch/other_file.md)
>      …you can use a relative link:
>
>      [a relative link](other_file.md)


### Jennifer Yoon -- to add  


### Any others?  

   

### Resources  

**Jennifer:** Bishop, Pattern Rec & ML,  c2006.  
Chp 5 is math of Neural Networks (p 225 book, p 245 in PDF format).  
http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop%20-%20Pattern%20Recognition%20And%20Machine%20Learning%20-%20Springer%20%202006.pdf

**Colleen:** Coursera, deeplearning.ai, class 1, back-prop:  
https://www.coursera.org/learn/neural-networks-deep-learning/lecture/6dDj7/backpropagation-intuition-optional  

**Jennifer:** Coursera, deeplearning.ai, class4, activation-functions:  
https://www.coursera.org/learn/neural-networks-deep-learning/lecture/4dDC1/activation-functions  

**Nathan:** "The partial derivatives for the softmax are hard to derive by hand.  For the 2-layer fully-connected NN, it took me many many pages of notes.  Please keep going even if you have to write out pages and pages of notes over multiple days to understand it.  I had to.   One of the annoying points is that almost nothing is a scalar; everything is a vector, matrix, or higher rank tensor.  So to properly do the partial derivatives you have to take something this guy Eli Bendersky calls the Jacobian: https://eli.thegreenplace.net/2016/the-softmax-function-and-its-derivative/ "  

**Andrew D:** Do CIFAR-10 Classifiers Generalize to CIFAR-10?  https://arxiv.org/abs/1806.00451  

**Andrew D:**  Tensorflow library automatically loads famous datasets into numpy arrarys.
https://www.tensorflow.org/api_docs/python/tf/keras/datasets/cifar10/load_data

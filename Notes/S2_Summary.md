## Neural Architecture

* **Neural Nets**

Neural Nets also called as Artificial Neural Network(ANN) are computing systems that can learn on its own. NNs generally perform supervised learning tasks, building knowledge from data sets where the right answer is provided in advance. The networks then learn by tuning themselves to find the right answer on their own, increasing the accuracy of their predictions.


![Simple Neural Network](https://miro.medium.com/max/1063/0*u-AnjlGU9IxM5_Ju.png)



* **Convolution Operation**

According to ![Wikipedia](https://en.wikipedia.org/wiki/Convolution), In mathematics (in particular, functional analysis), Convolution is a mathematical operation on two functions (f and g)that produces a third function expressing how the shape of one is modified by the other.

In CNN, Convolution is a image related operation between an image( later a convoluted one) and a Kernel that produces a convoluted image with shape calculated using the below formula.

![](https://miro.medium.com/max/660/0*_r70kZaBlXSyZzz5.)



* **Why do we add more layers?** 
 
In initial layers of CNN, it detects small features like **Edges and Gradients**. They then *make something complex out of it* and this loop goes on. This also depends on the task at hand. 

![MNIST Data](https://external-preview.redd.it/Dhrpp8M4X9BpyFOKGpD6uxl2aFRC3fBS-akgcZ2cxYw.gif?format=png8&s=8a9143099e235e11018e7adcadcb7b7973f5e4c1)


* **Intuition behind CNN Hierarchy**
Here I'm gonna relate CNN Hierarchy with *Words/Sentence* analogy

 1. Edges & Gradients   <----->  Letters
 2. Textures & Patterns <----->  Words
 3. Parts of Object     <----->  Sentences/Phrases
 4. Object Identifiers  <----->  Paragraphs
 5. Complete Object     <----->  Pages
 
 
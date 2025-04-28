# csc420-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CSC420 Assignment 2 Solved](https://www.ankitcodinghub.com/product/intro-to-image-understanding-csc420-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116890&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC420 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Instructions for submission: Please write a document (either pdf, doc, etc) with your solutions (include pictures where needed). Include your code inside the document. Please submit through MarkUs. You are expected to work on the assignment individually.

Max points: 15

1. [7 points] Implement seam carving:

(a) [1 point] Compute magnitude of gradients of an image

(b) [4 points] Find the connected path of pixels that has the smallest sum of gradients. A path is valid if it is connected (the neighboring points in the path are also neighboring pixels in the image), it starts in the first row of the image and in each step continues one row down. It finishes in the last row of the image.

(c) [1 point] Remove the pixels in the path from the image. This gives you a new image with one column less.

(d) [1 point] Remove a few paths with the lowest sum of gradients. Create a few examples and include them in your document.

You can find more details about seam carving in this paper:

S. Avidan and A. Shamir, Seam Carving for Content-Aware Image Resizing, SIGGRAPH 2007, http://www.win.tue.nl/~wstahw/edu/2IV05/seamcarving.pdf

2. [2 points] Image upscaling:

Write down the mathematical form of the convolution filter that performs upscaling of a 1D signal by a factor d. You do not need to write code. Please plot this filter (you can plot it by hand).

3. [6 points] Neural Network:

(a) [3 points] In the main.py script we provide a training pipeline for image classification on the MNIST dataset (digit classification). Please follow the readme file to download the MNIST dataset ( 50MB). Implement the forward pass for One-layer MLP and the cross entropy loss function with the requirement specified in the mlp.py. In particular, you are expected to implement cross entropy loss function, sigmoid, softmax functions and the init , forward functions for OneLayerNN class in mlp.py. You are only allowed to use numpy for this exercise.

(b) [3 points] Implement the backpropagation with gradient descent functions for OneLayerNN class in mlp.py and running main.py to train OneLayerNN. The function is used to first compute the gradient of the loss function with respect to the weight matrix and biases, and then run gradient descent using the specified learning rate. Please submit the training curves (the accuracy for every epoch) and the best accuracy you obtained. You can play

1

with different initializations and learning rates. You are also only allowed to use numpy for this exercise.

Additional credit [2 points]: Implement the functions init , forward and backpropagation with gradient descent for TwoLayerNN class in mlp.py, and submit the new training curve and the accuracy you get with a two layer MLP. You are expected to submit main.py and mlp.py for this problem.

2


Deep Learning (for Computer Vision - CS 763) Module - Spring 2017
===================

Course Information
------------------
Please refer to the <a href="https://www.cse.iitb.ac.in/~ajitvr/CS763_Spring2017/">CS763 Spring 2017</a> course page for general information. On this page, you will find specific information for the lectures that will be taught by <a href="http://www.cse.iitb.ac.in/~ajain/">Arjun Jain</a>.
<ul>
<li><b>Instructor:</b> <a href="http://www.cse.iitb.ac.in/~ajain/">Arjun Jain</a>
<li><b>Office:</b> 216, CSE New Building
<li><b>Email:</b> <i>ajain@cse DOT iitb DOT ac DOT in</i>
<li><b>Instructor Office Hours (in room 216 CSE New Building):</b> Arjun is on campus only on Fridays (and Saturdays for the 3 weeks during this course). Meet him after class or fix an appointment over email.
</ul>

Topics to be covered (tentative)
--------------------------------
<ul>
<li> The data-driven paradigm, feed forwards networks, back-propagation and chain rule
<li> CNNs and their building blocks -  ReLU, MaxPool, Convolution, CrossEntropy, etc.
<li> Vanishing gradients, residual blocks, visualizing and understanding CNNs
<li> CNN applications, CNN compression (and if time permits Siamese and Triplet networks) 
</ul>	

Learning materials and textbooks
--------------------------------
<ul>
<li> Lecture slides that will be regularly posted
<li> <a href = "http://www.deeplearningbook.org/">Deep Learning</a>, by Ian Goodfellow and Yoshua Bengio and Aaron Courville (freely downloadable!)
<li> All <a href="https://github.com/facebook/iTorch">iTorch</a> notebooks for topics covered in class can be found <a href="https://github.com/cs763-dl/2017Spring/tree/master/Notebooks">here</a>
</ul>

Tutorials and other useful resources
------------------------------------
<ul>
	<li> <a href="http://tylerneylon.com/a/learn-lua/">Learn Lua in 15 minutes</a>
	<li> <a href="https://github.com/torch/torch7/blob/master/doc/tensor.md">Torch's Tensor class</a>
	<li> <a href="https://github.com/torch/torch7/blob/master/doc/maths.md">Torch's math library</a>
	<li> <a href="https://github.com/terryum/awesome-deep-learning-papers">Awesome deep learning papers</a>
</ul>
	
Assignment
----------
We will use Kaggle to host the leader board for the assignment. You will be able to submit your model predictions <a href="https://inclass.kaggle.com/c/cse763-cifar10">on Kaggle</a> using your @iitb.ac.in email ids and check where you stand as compared to others in real time. Complete details about the assignment can be found <a href="https://github.com/cs763-dl/2017Spring/blob/master/Assignment/CS763-assignment-4.pdf">here</a>. Sample data can be downloaded from <a href="https://github.com/cs763-dl/2017Spring/raw/master/Assignment/CS763DeepLearningHW.tar.gz">here</a>. Due Date: 14 April 2017, 23:55.


Lecture Schedule: 
-----------------
<table>
  <tbody>
    <tr>
      <th>Date</th>
      <th>Topics</th>
      <th>Slides</th>
      <th>iTorch Notebooks</th>    
    </tr>
    <tr>
      <td>24/03/2017</td>
      <td>
	      <ul>
	      <li> Brief history/achievements of DL based algorithms</li>
	      <li> The data driven paradigm</li>
	      <li> Classification using k-nearest neighbor algorithm</li>
	      <li> Classification using a linear classifier</li>
	      <li> Optimization using vanilla gradient descent</li>
	      <li> Feed forward networks </li>
	      </ul>
      </td>
      <td><a href="https://github.com/cs763-dl/2017Spring/blob/master/Slides/Lec_1.pdf">Slides</a></td>
      <td>
	      <ul>
	      <li><a href="https://github.com/cs763-dl/2017Spring/blob/master/Notebooks/NN.ipynb">Vanilla kNNs</a></li>
	            <li><a href="https://github.com/cs763-dl/2017Spring/blob/master/Notebooks/manual_update.ipynb">Numerical Gradients</a></li>
	      </ul>
	  </td>
    </tr>    
    <tr>
      <td>25/03/2017</td>
      <td>
	      <ul>
	      <li> Chain rule/backward propagation</li>
	      <li> Torch7 nn.Module</li>
	      <li> Activation functions</li>
	      </ul>
      </td>
      <td><a href="https://github.com/cs763-dl/2017Spring/blob/master/Slides/Lec_2.pdf">Slides</a></td>
      <td>
	      <ul>
	      <li><a href="https://github.com/cs763-dl/2017Spring/blob/master/Notebooks/ReLU.ipynb">ReLU Activation Funciton</a></li>
	      </ul>
	  </td>
    </tr>
<tr>
<td>31/03/2017</td>
<td>
<ul>
<li> Fully Conncted Layer</li>
<li> Convolution Layer</li>
<li> Fully Connected as Convolution</li>
</ul>
</td>
<td><a href="https://github.com/cs763-dl/2017Spring/blob/master/Slides/Lec_4.pdf">Slides</a></td>
<td>
<ul>
<li><a href="https://github.com/cs763-dl/2017Spring/blob/master/Notebooks/Linear.ipynb">Fully Conncted Layer</a></li>
<li><a href="https://github.com/cs763-dl/2017Spring/blob/master/Notebooks/Convolution.ipynb">Convolution Layer</a></li>
</ul>
</td>
</tr>
<tr>
<td>1/04/2017</td>
<td>
<ul>
<li> Max Pool Layer</li>
<li> Cross Entropy Layer</li>
<li> Dropout Layer</li>
<li> Data Preprocessing and Augmentation</li>
<li> Weight Initialization</li>
<li> Baby Sitting the Learning Process</li>
<li> Hyper-parameter Optimization</li>
</ul>
</td>
<td><a href="https://github.com/cs763-dl/2017Spring/blob/master/Slides/Lec_4.pdf">Slides</a></td>
<td>
<ul>
<li><a href="https://github.com/cs763-dl/2017Spring/blob/master/Notebooks/MaxPool.ipynb">Max Pool Layer</a></li>
<li><a href="https://github.com/cs763-dl/2017Spring/blob/master/Notebooks/Dropout.ipynb">Dropout Layer</a></li>
<li><a href="https://github.com/cs763-dl/2017Spring/blob/master/Notebooks/WeightInit.ipynb">Weight Initialization</a></li>
</ul>
</td>
</tr>
  </tbody>
</table>




## Data description
All of the data is created manually and stored as form of excel file. The data is stored in multiple excel files for multiple information. Each part is an excel file. Each excel file has three columns, which are bug, the bug fix pattern from a prior study, and new bug fix pattern. The first column, bug, stores all the website links of Stack Overflow questions and Github commits, which contains deep learning bugs. The second column, bug fix pattern from a prior study, is the labels of bug fix pattern of the deep learning bug based on the prior study. However, these labels are applied to traditional programs, which is not suitable for Deep learning programs. Thus, we have created new appropriate labels for deep learning software. The last column, new bug fix pattern, is the new bug fix pattern label of each collected DNN bug.

Stack Overflow file stores all the bugs and bug fix patterns collected from Stack Overflow of five libraries.
Github file stores all the bug and bug fix patterns collected from Github commits of five libraries.
Caffe file stores the bug and bug fix patterns collected from Stack Overflow and Github commits of Caffe. 
Keras file stores the bug and bug fix patterns collected from Stack Overflow and Github commits of Keras. 
Tensorflow file stores the bug and bug fix patterns collected from Stack Overflow and Github commits of Tensorflow.  
Theano file stores the bug and bug fix patterns collected from Stack Overflow and Github commits of Theano.  
Torch file stores the bug and bug fix patterns collected from Stack Overflow and Github commits of Torch.  

## Data reproduction
To reproduce the result, we need to understand the definitions of all the labels of DNN bug fix pattern. Then, we access to the links of the bugs in the first column of each excel files. For Stack Overflow, we have to read the question, the answers, and the comments to collect enough information about the bug. After that, we can label the bug fix pattern based on the bug fix pattern label definitions. For Github, after access to each link, we can obtain the new code and old code in the Github commit. We have to understand the purpose of the modifications of a commit based on the program context. For example, the intent of the modification can be presented by the commit log or the method call. After that, we can decide the label of the bug fix pattern.

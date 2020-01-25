# Repairing Deep Neural Networks Fix Patterns and Challenges
The artifact is the labeled bug fix patterns of DNN bugs. The artifacts are the excel files, which are the bug fix patterns of DNN bugs collected from Stack Overflow and Github. Each excel file has three columns, which are bug, the bug fix pattern from a prior study, and new bug fix pattern. The bug column contains Github commits or Stack Overflow questions of the DNN bug. The bug fix pattern from the prior study column is the label of the DNN bug based on the prior study. However, these labels are applied to traditional programs, which is not suitable for Deep learning programs. Therefore, we have created new appropriate labels DNN software. The last column contains the new bug fix pattern label of each collected DNN bug.

To reproduce the result, we need to understand the definitions of all the labels of DNN bug fix pattern. Then, we access to the links of the bugs in the first column of each excel files. For Stack Overflow, we have to read the question, the answers, and the comments to collect enough information about the bug. After that, we can label the bug fix pattern based on the bug fix pattern label definitions. For Github, after access to each link, we can obtain the new code and old code in the Github commit. We have to understand the purpose of the modifications of a commit based on the program context. For example, the intent of the modification can be presented by the commit log or the method call. After that, we can decide the label of the bug fix pattern.

## Contact Lists
See [Contract.md](./CONTACT.md)

If you have any question, please contact the authors: [Md Johirul Islam] (mislam@iastate.edu) and [Rangeet Pan] (rangeet@iastate.edu) and [Giang Nguyen] (gnguyen@iastate.edu) and [Hridesh Rajan] (hridesh@iastate.edu)


## Bug Fix Pattern Data
The data can be found at ...

For more detail, please see [INSTALL.md](./INSTALL.md)

## License
This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE.md) file for details.

# Repairing Deep Neural Networks Fix Patterns and Challenges
The artifact is the labeled bug fix patterns of DNN bugs. The artifacts are the excel files, which are the bug fix patterns of DNN bugs collected from Stack Overflow and Github. Each excel file has three columns, which are bug, the bug fix pattern from a prior study, and new bug fix pattern. The bug column contains Github commits or Stack Overflow questions of the DNN bug. The bug fix pattern from the prior study column is the label of the DNN bug based on the prior study. However, these labels are applied to traditional programs, which is not suitable for Deep learning programs. Therefore, we have created new appropriate labels DNN software. The last column contains the new bug fix pattern label of each collected DNN bug.

To reproduce the result, we can access to the links of the bugs in the first column, bug. For Stack Overflow, we have to read the question, the answers, and the comments to collect enough information about the bug. Then, based on the definition of the bug fix patterns written in the paper, we can label the bug fix pattern. For Github, after access to each link, we can obtain the new code and old code in the Github commit link. We have to understand the purpose of the modifications of a commit based on the program context. After that, we can decide the label of the bug pattern.

The data can be found via ...

## Contact Lists

See [Contract.md](./CONTACT.md)

## License

[![MIT License](https://img.shields.io/github/license/xiaocong/uiautomator.svg)](http://opensource.org/licenses/MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Bug Fix Pattern Data

For more detail, please see [INSTALL.md](./INSTALL)
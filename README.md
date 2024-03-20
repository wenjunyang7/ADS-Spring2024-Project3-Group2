# Project 3 : Weakly supervised learning-- label noise and correction


### [Full Project Description](doc/project3_desc.md)

Term: Spring 2024

+ Group 2
+ Group members
	+ Wenjun Yang
	+ Licheng Wu
	+ Forain Zhang
	+ Yiwei Jiang


+ Project summary: In this project, , we created models to classify 50k images into 10 classes. Our dataset comprises labels, which contain some inaccuracies, and an additional set of 10k verified, error-free labels.
+ Model 1 constructs a convolutional neural network for classifying images into 10 categories. It layers convolutional blocks, each with ReLU activation, batch normalization, and dropout for complexity and overfitting control. The network ends with a dense layer for classification, optimized with Adam and evaluated by accuracy.
+ Model 2 corrects noisy labels using a specialized neural network, combining feature extraction with input noise handling. Then utilizes data augmentation, learning rate adjustments, and model checkpointing to improve performance, ultimately applying corrected labels to refine training on a mix of verified and initially noisy data, validated through K-Fold cross-validation.
	
**Contribution statement**:  Yiwei Jiang（33.3%）：Develop model1 & 2 ; evaluate model1&2  Forain Zhang（33.3%）：Develop model1，Evaluate baseline model  Wenjun Yang（33.3%）Make slides;presentation; Develop model1

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.

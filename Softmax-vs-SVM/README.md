In order to replicate the original paper, Deep Learning using Linear Support Vector Machines (Yichuan Tang) https://arxiv.org/abs/1306.0239, we decided to replicate by using the classification of MNIST Dataset using linear SVM with a Keras and a Tensorflow backend. The code can be found here https://github.com/hgupta01/svm_classification_keras or under the code section in paperswithcode https://paperswithcode.com/paper/deep-learning-using-linear-support-vector.

We used only the MNIST and the CIFAR-10 datasets and modified the code above to fit both datasets. 

The packages used to obtain these results were imported from a tensorflow and keras. In our A4.ipynb, you will see our experiments and results collected. Under a section in the A4 file called PAPER MODELS, we try to replicate the code using the repository stated above while fine tuning the parameters specified in the original paper. Each block of code represents a model that uses either softmax or svm layer on both datasets. And under the section called BEST MODELS, it is an updated modification of each model after we fine-tuned the hyperparameters and conducted ablation studies under the section called EXPERIMENTS. Each section so should have 4 blocks of code. To replicate the results, please run each block seperately.
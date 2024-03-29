# Experimental results of boosting DNN's robustness verification

The adversarial examples found by different attacking methods during the experiments on MNIST benchmark are at the [counter-examples](https://github.com/DNNBoosting/DNNBoosting/tree/master/counter-examples) folder. For each adversarial example file, its name is formatted as follows, where NUMBER is the indexed number of the image input, r1 is the ground truth, and r2 is the result of classification. For example, [NO0_origin_5_label_3.png](https://github.com/DNNBoosting/DNNBoosting/blob/master/counter-examples/Greedy/NO0_origin_5_label_3.png) in the [greedy](https://github.com/DNNBoosting/DNNBoosting/tree/master/counter-examples/Greedy) folder means that the adversarial image is 5 but misclassified to 3.

    [NUMBER]_origin_[r1]_label_[r2].png

We also made the following figure of the adversarial examples generated by different attacking methods and our greedy method. The figure under each figure is the classification result. The first line displays the original images correctly classified, and the remaining lines display the adversarial examples generated by different methods. As we can see, the adversarial examples generated by the greedy method are closer to the original ones.

![comparision](https://github.com/DNNBoosting/DNNBoosting/blob/master/Comparison.png)

# Classical-And-Quantum-Neural-Networks

Research Paper Preprint - https://www.researchgate.net/publication/394016372_Classical_and_Quantum_Neural_Networks

1. Quantum Inspired Everett's Healey Neural Network - Classification Accuracy with Post Processing - 88 to 90 Percent with Post Processing
   (still does not cross the linear threshold , but with more advanced classical post processing to especially classify the unique test which are the        most misclassified is needed.)
   Note - The probability amplitude criteria of threshold 0.707 for bit mesurement is strict step function but in quantum computers either bit can still occur , so on actual quantum computer multple measurements per input vector will be needed to trace all the paths and then get the output counts of measurement and see which is greater , and as per that the input is classified by comparing with targets and other criterias discussed in the code.

3. Lagrangian Per Sample Plus Chebyshev NN -
   1. Direct Training of the Lagrangian Vectors Per sample without regularization leads to Overfitting as they are not on the same 2D Manifold..
   2. Direct Training PLus Regularization - Same Accuracy if one does Lagrangian Per Sample Training with the Margin Loss function without regularization (This is not per class Lagrangian Vectors and        different strategies as done in Best NN as Lagragian NN Paper)...(Experimental Observation) One can research on new loss functions to increase the classification accuracy of Probabilistic              Interpretation Circuit of NN / Lagrangian NN as an alternative to Margin Loss , or different kind of regularization...Also this decrease in accuracy also occurs as the test data can create             unique outputs not in train unique or train shared , and this leads to misclassification , if one refers the Quantum Everetts Inpsired NN , the same phenomenon is observed here , so better             frequentist based approach can also lead to increase in the accuracy of the LAgrangian NN , for Unique Tests...Also this is the max accuracy that the SOTA using Quantum Linearized Networks can         reach if trained directly ... further research is needed in this ...As batch size is decreased the test accuracy increases... At higher batch size overfit occurs faster i.e. at lesser epochs...
   3. Chebyshev Continuous Activation based Lagrangian Training with Regularization - Reaches the accuracy as achieved by using NN alone , hence this joint system training of Chebyshev and Lagrangian        NN acts as two way substitute to the NN , one via Lagrangian NN and one via Chebyshev NN , The trained polynomial activation functions particularly for the dataset are also plotted...
      Here though the Lagrangian Vectors per layer lie on the same manifold of the Chebyshev Activstion in that layer, we have no means other than frequentist approach to infer on the test data , as
      we dont know the Lagragian vectors for it , unless we pass it throught the chebyshev Activation and find the Lagrangian Vectors explicitly for the test vectors and hence further reaseach is            needed to get SOTA out of just the Lagrangian NN , in loss function or the frequentist approach (this can also help in SOTA Paper of HQAI direct training , or Quantum Everett NN Frequentist            Approach)
   4. Approach 3 is implemented for CIFAR as well - One can change the width and depth of the architechture and instead of target states combined use one hot label encoding
      Here more deeper Lagragian as well Chebyshev NN can be used , also instead of basic NN , one can use Convolutional Lagrangian/Chebyshev NN ,or Transformer Lagrangian/Chebyshev NN terms coined          based on this work for getting higher accuracy of classification , to get both the Probabilistic (Lagrangian Per Sample) and the Deterministic Inpterpretation (Chebyshev Activation NN) of NN ...
5. Multivariate Taylor/Chebyshev Basis NN
6. Recurrent Polynomial NN(Direct Training)
7. Chebyshev NN (Direct Training)

PS - All the five types discussed in the paper will be uploaded later- 

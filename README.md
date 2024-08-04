# Deep_Learning-SE4050_Lab02
## Ex 01
i) When iterations = 100

  W1 = [[0.1826 0.2304]
   [0.2705 0.3217]] 
  
   W2 = [[-1.819  -1.769 ]
   [ 1.1239  1.1739]] 
  
   Output = [[0.178  0.8771]] 
   Desired output = [[0.01 0.99]] 
   Error = 0.020492276763740064
     When iterations = 500 --> Error = 0.0027379998349943094

ii) When iterations = 500

  W1 = [[0.2266 0.2733]
   [0.3085 0.3611]] 
  
   W2 = [[-2.7649 -2.7149]
   [ 1.7767  1.8267]] 
  
   Output = [[0.0646 0.94  ]] 
   Desired output = [[0.01 0.99]] 
   Error = 0.0027379998349943094

iii) When iterations = 5000

  W1 = [[0.289  0.3348]
   [0.3885 0.4428]] 
  
   W2 = [[-3.7201 -3.6701]
   [ 2.6755  2.7255]] 
  
   Output = [[0.0212 0.979 ]] 
   Desired output = [[0.01 0.99]] 
   Error = 0.00012291694588416547

## Ex 02

1)	Accuracy will be increased.
2)
Accuracy for 50 hidden units: 90.25 %
Accuracy for 500 hidden units: 90.75 %
Accuracy for 350 hidden units: 90.5 %
Accuracy for 300 hidden units: 90.25 %
Accuracy for 200 hidden units: 91.0 %
Accuracy for 250 hidden units: 91.0 %
Accuracy for 270 hidden units: 91.0 %
Accuracy for 280 hidden units: 90.25 %
Accuracy for 275 hidden units: 91.0 %

When the number of hidden nodes increases, accuracy initially improves because the network can learn more complex patterns. However, after a certain point, increasing hidden nodes further doesn't significantly change accuracy. If the hidden nodes are increased too much, the accuracy can decrease due to overfitting, making the network too complex and less effective on new data.

## The working of this is bit counter intutive to understand 

![Image](https://github.com/Anshuman-37/MLIS_2/blob/main/examples/intro/Neural_Representaino.jpg?raw=true)


So according to the code we have 

- There is Neural Network for inputs for Xor function and it is output as the target vector/label
- We first try to use precomputed answer using RELU as activation function and get zero loss 
- But we have to try it with sigmoid
- There is also catch here we are adding baises as first row of the feature vector to save some computational resources 
- This is a bit intutive to get but you can get a better understanding what is happening 
- Then just keep following the dimensions of the array 
- When you use sigmoid we wont get the answer becaue XOR is linearly inseperable
- and we get the output vector as [0.5,0.5,0.5,0.5] because we are unable to get a decision boundary 


# Note - This is all according to me, I may be wrong so don't believe it blindly.

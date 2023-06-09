# ERA_BackProp

## Part1

### Steps to update gradient and parameters

####Block1: Calculates forward propagation. The error for E1 and E2 are added
####Block2: Calculates the gradient of Loss Function with respect to w5(parameter)
####Block3: The calculation involves chain rule from E1 (as E2 is not affected by W5) to a_o1 to o1 To w5
####Block4: The calulation is done to calculate gradients for weights of innitial layers (w1)
####Block 5: Gradient for all weights in innitial layers are calulated

#### Updating loss
Once the gradients are calculated, they are updated after multiplying with learning rate
This gets us the new weights

## Part2

#### The notebook for running MNIST is attached


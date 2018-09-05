# neural-network-overview

## Why Neural Networks?

https://www.youtube.com/watch?time_continue=15&v=zAkzOZntK6Y


## Neural Network Architecture
___

### Neural Network Architecture Overview

Ok, so we're ready to put these building blocks together, and build great Neural Networks! (Or Multi-Layer Perceptrons, however you prefer to call them.)

This first two videos will show us how to combine two perceptrons into a third, more complicated one.

* https://www.youtube.com/watch?time_continue=3&v=Boy3zHVrWB4
* https://www.youtube.com/watch?v=FWN3Sw5fFoM

### Multiple layers
Now, not all neural networks look like the one above. They can be way more complicated! In particular, we can do the following things:

Add more nodes to the input, hidden, and output layers.
Add more layers.
We'll see the effects of these changes in the next video.

* https://www.youtube.com/watch?v=pg99FkXYK0M

### Multi-Class Classification

And here we elaborate a bit more into what can be done if our neural network needs to model data with more than one output.

* https://www.youtube.com/watch?v=uNTtvxwfox0

## Feedforward
___

### Feedforward Overview

Feedforward is the process neural networks use to turn the input into an output. Let's study it more carefully, before we dive into how to train the networks.

* https://www.youtube.com/watch?v=hVCuvMGOfyY

### Error Function
Just as before, neural networks will produce an error function, which at the end, is what we'll be minimizing. The following video shows the error function for a neural network.

* https://www.youtube.com/watch?time_continue=1&v=SC1wEW7TtKs

## Backpropogation
___

### Backpropogation Overview

Now, we're ready to get our hands into training a neural network. For this, we'll use the method known as backpropagation. In a nutshell, backpropagation will consist of:

* Doing a feedforward operation.
* Comparing the output of the model with the desired output.
* Calculating the error.
* Running the feedforward operation backwards (backpropagation) to spread the error to each of the weights.
* Use this to update the weights, and get a better model.
* Continue this until we have a model that is good.

Sounds more complicated than what it actually is. Let's take a look in the next few videos. The first video will show us a conceptual interpretation of what backpropagation is.

* https://www.youtube.com/watch?time_continue=1&v=1SmY3TZTyUk

### Backpropagation Math

And the next few videos will go deeper into the math. Feel free to tune out, since this part gets handled by PyTorch pretty well. If you'd like to go start training networks right away, go to the next section. But if you enjoy calculating lots of derivatives, let's dive in!

In the video below at 1:24, the edges should be directed to the sigmoid function and not the bias at that last layer; the edges of the last layer point to the bias currently which is incorrect.

* Calculating the Gradient: https://www.youtube.com/watch?v=tVuZDbUrzzI

#### Chain Rule

We'll need to recall the chain rule to help us calculate derivatives.

* https://www.youtube.com/watch?v=YAhIBOnbt54

* Calculating the Gradient pt.2: https://www.youtube.com/watch?v=7lidiTGIlN4

### Calculation of the derivative of the sigmoid function
Recall that the sigmoid function has a beautiful derivative, which we can see in the following calculation. This will make our backpropagation step much cleaner.

* https://d17h27t6h515a5.cloudfront.net/topher/2017/September/59b6ffad_sigmoid-derivative/sigmoid-derivative.gif


## Training Optimization
* https://www.youtube.com/watch?time_continue=24&v=UiGKhx9pUYc

## Testing

* https://www.youtube.com/watch?v=EeBZpb-PSac

## Overfitting and Underfitting

* https://www.youtube.com/watch?v=xj4PlXMsN-Y


## Early Stopping (Model Complexity Graph)

* https://www.youtube.com/watch?v=NnS0FJyVcDQ


## Regularization

* https://www.youtube.com/watch?v=KxROxcRsHL8

* https://www.youtube.com/watch?v=ndYnUrx8xvs


## Dropout

* https://www.youtube.com/watch?v=Ty6K6YiGdBs

## Local Minima

* https://www.youtube.com/watch?v=gF_sW_nY-xw

## Vanishing Gradient

* https://www.youtube.com/watch?time_continue=1&v=W_JJm_5syFw


## Other Activation Functions

* https://www.youtube.com/watch?v=kA-1vUt6cvQ
* Correction: For the plots of tanh() and relu() in the first half of the video, the origin should be labeled with a value _y_ = 0, not 0.5.

## Batch VS Stochastic Gradient Descent

* https://www.youtube.com/watch?v=2p58rVgqsgo

## Learning Rate Decay

* https://www.youtube.com/watch?time_continue=4&v=TwJ8aSZoh2U


## Random Restart

* https://www.youtube.com/watch?time_continue=3&v=idyBBCzXiqg


## Momentum

* https://www.youtube.com/watch?time_continue=4&v=r-rYz_PEWC8

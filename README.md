# Pytorch-MNIST Sample Notebook

## File Structure
pytorch-mnist.ipnyb is jupyter notebook for running sample code to train and eval MNIST Digit Recognition Task

## Reference
* https://github.com/jiuntian/pytorch-mnist-example

learning_rate = 0.01
momentum = 0.9
device = "cpu"
model = CNN().to(device) #using cpu here
optimizer = optim.SGD(model.parameters(), lr=learning_rate,
                      momentum=momentum)

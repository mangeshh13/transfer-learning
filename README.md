Case Study : Transfer Learning

Train a image classifier for CIFAR-10 dataset in the following setting:

1. Prepare a CIFAR-5 subset for classes: ['airplane', 'automobile', 'bird', 'cat', 'deer']
2. Train a classification head and note the performance on the CIFAR-5 subset (from step 1) by:
   
   2.a Using a pretrained resnet18 or mobilenet_v2 model as back-bone (i.e. all layers are frozen)
   
   2.b Using a pretrained resnet18 or mobilenet_v2 model as back-bone with last group or 3-4 layers un-frozen/available for training
4. Provide commentary on what was observed between the models trained for step 2.a and 2.b

# Federated Learning

This is an introductory example of using Federated learning approach to Data Privacy in ML.
The sample is from different datasets for Breast Cancer research 
and gives us an introductory view into using Colab, PyTorch and PySyft.

There is stil more work to be done on the privacy because 
this sample is really meant to show how the learning process works when you're pulling from separate datasets, 
so this process actually doesn't ensure privacy! 

One option is to call model.get() to learn about how to predict well on Alice's data without having seen it,
which can help you learn more about the dataset itself, even potentially replicating it perfectly.

A way to avoid this is to average Bob and Alice's model updates before sending them to the global model
as per the video! 

Thanks to u//raj111sam for pointing this out on the r/artificial subreddit.


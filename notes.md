# Continous Research Journal

### Naveen Kuppuswamy

## 12/26/2019

Had a few ideas today on how to tackle the current bad results from the bubble classifier. These are listed below with a difficulty rating of 0-10 in parenthesis:

1. Retrain with new data without normalization (1): Seems an obvious first step to try properly
2. Implement k-fold cross validation (6): No idea how to do it and might take me forever
3. Implement single image classifier (5): Lots of re-plumbing to do but can be done. Not sure if 2 CUDA based classifiers processes can run in parallel. I was thinking we could average the classification results from each bubble weighted by validation dataset performance.
4. Try RESNet50 (4): Maybe bigger network is the way to go. Requires only a bit of tweaking to setu
5. Properly re-implement RGB training (5): Not sure what went wrong last time and afraid debugging will bog me down.
6. Remove random flipping and try other randomization transform options (3/5) : Random flipping might be hurting my generalization. Maybe better to try out other kinds of random noise




# FinalNet
##**Isela Juarez-Cendejas**

**Initial Model:**
The model that I first designed only had two layers and achieved an accuracy of 74%.

Going off that model, I added another 4 layers making my second model have a total of 6 layers. The total accuracy ended up being about 88%. It is 14% better compared to the initial model.

**Final Model:**
The final model ended up being 8 convolutional layers with 2 fully connected layers and dropout.

Also, for the final model, I increased the batch size and added some randomness to the data augmentation like: RandomHorizontalFlip and RandomCrop.

Then, I also added a schedular that took in the optimizer variable from my last code, step_size of 20 and a gamma value of 0.1.

All of this ended up giving me an accuracy of 90% which was not that much of an increase (2%) but still a huge improvement from the intital model. To further improve this in the future and for any model for that matter, I realize that a bit more randomness and normalization to the training data makes a big difference in performance as well as the optimizers used which in my case did increase the accuracy.

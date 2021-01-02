# self-supervised_learning

This file will accomodate codes for my diploma thesis in which I am working on Self-Supervised tasks.

## ROTATION pretext task

I used rotation pretext task on CIFAR10 dataset to try my first Self-Supervised learning experiment with ResNet architecture. Rotation pretext task consist of rotating images in random steps of 0, 90, 180 or 270 degrees with aim that model will learn representations of pictures better. 

![rotation_pretext_task_method](/images/rotation_pretext_task_method.png)

After this pretext task I test 2 models - one with SSL pretext task and another one without. On the graphs you can see, that model with SSL pretext task has better accuracy with fewer labeled pictures.

![rotation_pretext_task](/images/rotation_pretext_task.png)

#hessian
Experiments on computationally efficient algorithm for non-convex optimization

Log:

2016/02/20: 02:00  setting up. test powermethod.

2016/02/21: 01:30  review on torch. did http://torch.ch/docs/five-simple-examples.html

2016/02/22: 05:00  Read the source code of cifar, mnist, cifar(92.4%) to develop my train() function. Read optim. Read oxford pratical4. Watch this https://www.youtube.com/watch?v=NUKp0c4xb8w. Start writing train().   

2016/02/23: 01:30  Read the source code of cifar, mnist, cifar(92.4%). Continue my train()

2016/02/24: 00:30  Read the source code of confusion matrix.  

2016/02/26: 00:15  Finished train.lua 
            00:40  Started provider.lua. Read the source code for dataloading( mnist, cifar10 )
            01:00  Developed data loading script. Investigated data format in mnist, cifar.

2016/02/29: 01:00  Ran an experiment on how the gradient will change for mnist training (2000 size instead of 10000)

2016/03/12: 00:40  Learned plotting function (gnuplot) and paths library (Filename Manipulation Package)
            01:00  Learned folder directory management in computational experiments

2016/03/13: 02:00  Started writing runall.sh file to manage an experiment in one run of a script. 
            03:00  Continued to develop runall.sh. 

2016/03/14: 02:00  Confirmed gradParameters are collected at every mini batch. As the mini-batchsize increases, the norm of gradParameters will be smoother.
                   Developed runall.sh so that it will automatically move itself to the output folder. 
            01:00  Determined the threshold as 0.5
            02:00  Developed HessianPowerMethod.lua 
            02:00  Developed HessianPowerMethod.lua

2016/03/15



            

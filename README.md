# ball_vs_block_machine_learning

The unsupervised file in the code is just running the simulation with a ball and a block. When the ball hits the block score is incremented. Also a table gets generated based on different parameters of ball and the block and the result whether a hit occured or not.

![image](https://user-images.githubusercontent.com/20777854/116067922-44dcc380-a6a7-11eb-99ee-3128908e685f.png)

This proect will be extended, soon I will be adding another file with supervised code , where a model will be trained using the success data. And future speed of ball will be calculated based on that to maximize the number of successful hits.

Here's how the captured data looks:

![image](https://user-images.githubusercontent.com/20777854/116068428-dd734380-a6a7-11eb-99af-fcbb834a7cb5.png)

[Update] Added the file containing teh supervised one. It has two modes of training , one where training set is prepared from formula, so in this case we only see success cases while training, the anothe case is sequencial where the ball gets sequencial times, in this way of training we see both success and failed cases however only success cases are used as training set.

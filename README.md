# Analytics-4

## About 
AWS DeepRacer is a 1/18th scale race car which gives you an interesting and fun way to get started with reinforcement learning (RL). With AWS DeepRacer, you now have a way to get hands-on with RL, experiment, and learn through autonomous driving. You can get started with the virtual car and tracks in the cloud-based 3D racing simulator. For a real-world experience, you can deploy your trained models onto AWS DeepRacer and race in the global AWS DeepRacer league, the world’s first global autonomous racing league for developers.

## Steps to deploy DeepRacer 
1. Sign into the console (https://aws.amazon.com/deepracer/)
2. Click the Get Started / Create Model button on the right
3. Create resources, if they aren't created yet
4. Name and describe your model
5. Choose an environment 
Where the training occurs; in our case, a simulated track.
6. Select action space
This lists out all of what the agent can actually do at each timestep.
7. Select reward function
An agent receives something from this in order to learn the appropriate actions to take.
8. Tune hyperparameters
Includes specific settings for our training, such as batch size, epochs or learning rate.
9. Set stop condition
This causes training to cease, whether it's time-based, an action, or other options.
10. Evaluation 

* Note: While the evaluation job is running, watch the live results in the simulator. Remember to look at what your car seems to be doing well versus not so well.

## clone Model 
From the Action dropdown, select Clone.
Use the previous experiences(Model)

## Download 
Click Download model. The downloaded file will reference the name of your model with the

## SageMaker 
Amazon SageMaker RL builds on top of Amazon SageMaker, adding pre-packaged RL toolkits and making it easy to integrate any simulation environment. As you would expect, training and prediction infrastructure is fully managed, so that you can focus on your RL problem and not on managing servers.

1. Sign into the console (https://aws.amazon.com/sagemaker/features/)
2. Launch NoteBook Instance or Amazon SageMaker Studios (choose the machine configurations)
3. Clone your git repository 
4. Set the environment and dependancies 
5. Create  IAM role 
6. Run the Sagemaker.ipynb(src conations the train and evolution )
7. Model will be save to S3 (set up Boto3)

## References 

* For more information about AWS DeepRacer, see https://aws.amazon.com/deepracer/.
* To troubleshoot and collaborate about the AWS DeepRacer, see the AWS DeepRacer forums.
* https://www.classcentral.com/course/udacity-aws-deepracer-17236
* https://aws.amazon.com/blogs/aws/amazon-sagemaker-rl-managed-reinforcement-learning-with-amazon-sagemaker/
* https://github.com/avinashronanki/Rl-basics
* https://github.com/romeokienzler/DeepRL

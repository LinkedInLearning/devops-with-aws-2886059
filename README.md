# DevOps with AWS
This is the repository for the LinkedIn Learning course DevOps with AWS. The full course is available from [LinkedIn Learning][lil-course-url].

![DevOps with AWS][lil-thumbnail-url] 

DevOps describes a culture and set of processes that bring development and operations teams together to simplify software development. It allows organizations to create and improve products at a faster pace than they can deliver with traditional software development approaches. And it’s gaining in popularity at a rapid rate. In this course, programmer Dipali Kulshrestha covers the concepts of DevOps with hands-on demos to create and automate CI/CD (continuous implementation and continuous delivery) pipelines. She covers AWS services like CodeCommit, CodeBuild, CodeDeploy, and CodePipeline, and how to implement DevOps with AWS offerings to increase security, scalability, reliability, and simplicity of the development processes.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"



### Instructor

Dipali Kulshrestha 
                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/dipali-kulshrestha).

[lil-course-url]: https://www.linkedin.com/learning/devops-with-aws
[lil-thumbnail-url]: https://cdn.lynda.com/course/2886059/2886059-1626198010037-16x9.jpg

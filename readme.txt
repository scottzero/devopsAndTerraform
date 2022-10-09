how the project works: 

>we write out code for an api
>push the code to github
>github then triggers a build in azure devops pipeline
>azure devops pipeline is going to build our docker image of our app 
>which will then push the image to docker hub
>then thepipeline will use terraform to provision the infrastrcuture in azure portal, and deploy our docker image to that infrastrcuture 
(and this is all automated, the only manual step is pushing the code up to github)


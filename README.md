# Jenkins-CICD-Multi-stage-pipeline Project





# Install Plugins
Install Pipeline and SSH Build Agents plugin. 
![image](https://github.com/Skillz619/Jenkins-CICD-Project/assets/43133388/9d0eeed4-e532-4bea-91f1-d07e204c3a48)


# Add credentials
We add a credntial
![image](https://github.com/Skillz619/Jenkins-CICD-Project/assets/43133388/868c32c5-1560-4db3-b603-2b3b7fa448a6)

# Add nodes
Create a dev node and launch via ssh with the credentials created
![image](https://github.com/Skillz619/Jenkins-CICD-Project/assets/43133388/166284b7-84e5-4639-8110-0c3d83eab6f4)

Create a prod node and launch via ssh with the credentials created
![image](https://github.com/Skillz619/Jenkins-CICD-Project/assets/43133388/80f9990b-d2d4-4b1c-8164-8736af24f236)


Both dev and production server nodes created
![image](https://github.com/Skillz619/Jenkins-CICD-Project/assets/43133388/54de733b-9827-46ea-9ec8-cbb671ffaeb6)

# Create and Configure the job:

In new item we create a pipeline job
![image](https://github.com/Skillz619/Jenkins-CICD-Project/assets/43133388/050265b0-df6b-444a-b663-a5b81c881150)

<a href="https://github.com/Skillz619/Jenkins-CICD-Project/blob/main/jenkinsfile"> Add pipeline Script in the pipeline job 
![image](https://github.com/Skillz619/Jenkins-CICD-Project/assets/43133388/06b294ec-dc77-47c5-98fc-4f131d056288)

Save the job and build it
![image](https://github.com/Skillz619/Jenkins-CICD-Project/assets/43133388/b8201ff1-9b47-49cd-8e65-11f5c375035c)


✅Run the pipeline job.

✅Check job configuration and output.

✅Test Dev app.

✅Test Prod app.

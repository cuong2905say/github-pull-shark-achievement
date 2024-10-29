# Github Pull Shard Achievement Gainer
Starting without leaving your browser

TL;DR
## 1. Fork my repository
<br>
Click Fork button

![image](https://github.com/user-attachments/assets/080c7767-aa71-4abe-8fb1-fc5a1f4fa1f9)

---
Make it your own repository !!

![image](https://github.com/user-attachments/assets/a204f373-291f-43b9-8b77-91e5c182367a)

## 2. Create Personal Access Token (PAT)

Instead of using github action for authoriation, this action need your PAT to specify that you are the author of the pull request and github will count it.

#### 2.1. Click to your avatar (top right corner) then click Settings.

![image](https://github.com/user-attachments/assets/efffb05f-c2a1-43f8-959a-282033702d8b)

#### 2.2 The last tab is Developer Settings

![image](https://github.com/user-attachments/assets/3601610b-381d-493b-835a-fc1f457c135e)

#### 2.3 Generate a classic token

![image](https://github.com/user-attachments/assets/61592210-11a7-4032-bf57-48b553e0eb78)
***
![image](https://github.com/user-attachments/assets/4d39511f-ebed-4b2f-99b8-7f788e8d99df)

#### 2.4 Grant permission for PAT
You need to click with some permission: repo, user, project.

![image](https://github.com/user-attachments/assets/1030d123-20c4-4fa8-b282-7efc4e464e36)
***
![image](https://github.com/user-attachments/assets/731737a1-433c-46fb-99f6-5e1bef47260a)

## 3. Update the secrets in Github action
Back to the repository you've forked. Go to setting the Secrets.

![image](https://github.com/user-attachments/assets/e64b9327-56ba-4d51-af9b-3c18157c02ab)

***

And then, create a new secret, named **PAT**, then paste the token you saved in previous step.

## 4. Run Github actions workflow

I am setting the workflow trigger as workflow_dispatch, so you need to run it manually.
![image](https://github.com/user-attachments/assets/3c05380a-f9be-4b06-b799-e6b7598866fe)

## 5. Relax and give me back a star !! You can delete this repository or make it private.

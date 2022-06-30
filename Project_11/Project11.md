-Step 1:   INSTALL AND CONFIGURE ANSIBLE ON EC2 INSTANCE


- 1:  Update Name tag on your Jenkins EC2 Instance to Jenkins-Ansible
![image](https://user-images.githubusercontent.com/94152732/176484201-10ba5fff-e40d-4697-b166-0297f4d479fc.png)

- 2: In your GitHub account create a new repository and name it ansible-config-mgt.
![image](https://user-images.githubusercontent.com/94152732/176485237-2015723b-ef24-4a36-a239-8a947997c8eb.png)

- 3: Install Ansible
![image](https://user-images.githubusercontent.com/94152732/176486466-855460ef-9118-4e23-b2c7-37cf667244fe.png)
![image](https://user-images.githubusercontent.com/94152732/176486644-bc9c4893-51d4-4421-a75d-d2d0e4919090.png)
![image](https://user-images.githubusercontent.com/94152732/176486802-60d1a6b6-ddaf-47b6-b390-9b5abffcdf85.png)
![image](https://user-images.githubusercontent.com/94152732/176486988-4c843ebb-4dc1-4671-bba7-3b977559ff02.png)
![image](https://user-images.githubusercontent.com/94152732/176493970-6839eee9-95ad-4923-b42b-120d83655fc2.png)

- 4: Configure Jenkins build job to save your repository content every time you change it 
![image](https://user-images.githubusercontent.com/94152732/176494218-c2012c01-ba91-4b1d-bb10-c89ef6033359.png)
![image](https://user-images.githubusercontent.com/94152732/176494961-232f05ab-dccd-45d5-b7fa-ea7c3311a1ba.png)
![image](https://user-images.githubusercontent.com/94152732/176496142-39b1deb2-5f47-4442-8507-366860ffd76f.png)
![image](https://user-images.githubusercontent.com/94152732/176509505-895ea985-0959-4473-99a0-cfa69659e913.png)

- 5: Test your setup by making some change in README.MD file in master branch and make sure that builds starts automatically and Jenkins saves the files (build artifacts) in following folder

![image](https://user-images.githubusercontent.com/94152732/176509894-0c97c569-e928-45dd-94d7-d8e83efee348.png)
![image](https://user-images.githubusercontent.com/94152732/176510888-9ebe8699-af6f-4107-8b54-f0be91fbc2da.png)


- Step 2: Prepare your development environment using Visual Studio Code

![image](https://user-images.githubusercontent.com/94152732/176511447-438d00a4-6720-4131-9e0f-3f43728d5fa8.png)

- BEGIN ANSIBLE DEVELOPMENT




-1: In your ansible-config-mgt GitHub repository, create a new branch that will be used for development of a new feature.

![image](https://user-images.githubusercontent.com/94152732/176514537-1a381aa3-569d-4b3d-8ca4-5e786c9f3f19.png)

- 2: Checkout the newly created feature branch to your local machine and start building your code and directory structure
![image](https://user-images.githubusercontent.com/94152732/176517944-bf10b4a8-b76b-4446-bbb2-bd6747367f2e.png)


- 3: Create a directory and name it playbooks – it will be used to store all your playbook files.
![image](https://user-images.githubusercontent.com/94152732/176518279-8b355c1a-f1d3-43b7-ab84-6ce1ceeea281.png)


- 4: Create a directory and name it inventory – it will be used to store all your playbook files.
![image](https://user-images.githubusercontent.com/94152732/176518311-11a6c5a9-d520-450d-b5cc-5987a84734f4.png)

- 5: Within the playbooks folder, create your first playbook, and name it common.yml
![image](https://user-images.githubusercontent.com/94152732/176518594-16623ae5-0ba5-4edb-b595-7a91f2990cda.png)

- 6: Within the inventory folder, create an inventory file (.yml) for each environment (Development, Staging Testing and Production) dev, staging, uat, and prod respectively.

![image](https://user-images.githubusercontent.com/94152732/176519014-995d7a04-3aad-4a64-988b-647fa1c0c7d5.png)

Step 4: Set up an Ansible Inventory

![image](https://user-images.githubusercontent.com/94152732/176530007-45623e3e-e16f-46b3-a123-24c3260d9f27.png)
![image](https://user-images.githubusercontent.com/94152732/176531714-92d00092-d8bf-4423-bd84-f18aa38bd02d.png)
![image](https://user-images.githubusercontent.com/94152732/176533516-8d5680d6-02d3-4807-b4a8-e9d059643c7f.png)
![image](https://user-images.githubusercontent.com/94152732/176535085-eb355d81-47b8-4fdd-9fae-b462074e08f9.png)


- Step 5: Create a Common Playbook
![image](https://user-images.githubusercontent.com/94152732/176536508-aa23e75f-b91c-44b0-97a9-3bae6df4f50a.png)

- Step 6: Update GIT with the latest code

![image](https://user-images.githubusercontent.com/94152732/176540372-e2b70ca6-20e9-4a19-a7f1-c02d90d532de.png)
![image](https://user-images.githubusercontent.com/94152732/176541570-6e792a34-1ddf-495c-ab1f-de56e3fb63b6.png)
![image](https://user-images.githubusercontent.com/94152732/176543348-09e15967-936b-4ee3-bb27-50d4f9391497.png)
![image](https://user-images.githubusercontent.com/94152732/176543561-00f72f5b-b425-4972-bfd5-3cd3b0dfb499.png)
![image](https://user-images.githubusercontent.com/94152732/176543713-9eb2be4d-60c1-470a-b0c8-637b6a0ea53b.png)
![image](https://user-images.githubusercontent.com/94152732/176544120-579894db-d135-42fc-8837-b25db314269a.png)
![image](https://user-images.githubusercontent.com/94152732/176544590-34665a94-ca57-4c3f-9ccb-36be8dd57162.png)


- Step 7 – Run first Ansible test

![image](https://user-images.githubusercontent.com/94152732/176674791-a30e8183-f7c7-455e-9bde-af51dfc2f674.png)
![image](https://user-images.githubusercontent.com/94152732/176675316-4d9d6d19-9889-42bb-b8b4-09c2088da512.png)
![image](https://user-images.githubusercontent.com/94152732/176675415-4a6cee13-548a-418f-a508-ac69c531b9eb.png)
![image](https://user-images.githubusercontent.com/94152732/176675575-5c089538-b3eb-40e7-9487-2d8863ba5f5e.png)
![image](https://user-images.githubusercontent.com/94152732/176675617-287914f1-47d5-49aa-8395-abaa50da819b.png)
![image](https://user-images.githubusercontent.com/94152732/176675668-2a990c16-26b2-4e83-a530-73ca2ce4fc1d.png)

 - Updated ansible playbook with some new Ansible task and go through the full

![image](https://user-images.githubusercontent.com/94152732/176680580-c678ed8b-6f8a-48b5-ac0a-845980a265a3.png)



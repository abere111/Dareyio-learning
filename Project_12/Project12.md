- Step 1 – Jenkins job enhancement

- 1 : Created ansible-config-artifact directory
 ![image](https://user-images.githubusercontent.com/94152732/176972317-5318fe52-3044-4391-b3f1-26ca1f461302.png)

- 2: Change permissions to this directory
![image](https://user-images.githubusercontent.com/94152732/176972641-e8d782d6-a837-4bf0-888d-5ce089e8b3a9.png)

- 3: Go to Jenkins web console -> Manage Jenkins -> Manage Plugins -> on Available tab search for Copy Artifact and install this plugin without restarting Jenkins
![image](https://user-images.githubusercontent.com/94152732/176972995-49bd5c3d-1718-4c4b-b015-0ac88ebdee7a.png)

- 4: Create a new Freestyle project
![image](https://user-images.githubusercontent.com/94152732/176973315-74188660-c1d5-4b5e-8f52-e29af8ec254a.png)

- 5: Job Configuration
![image](https://user-images.githubusercontent.com/94152732/176973842-2728cc2f-171f-4b1a-b3f4-dc8a47111b03.png)
![image](https://user-images.githubusercontent.com/94152732/176973859-3c0850b1-2bde-422b-8349-48f9cd8f8297.png)

- 6: 
![image](https://user-images.githubusercontent.com/94152732/176974577-40092442-c443-4b85-a8ef-d8b34ab38f73.png)

- 7: Test Set up in Artifact Directory
![image](https://user-images.githubusercontent.com/94152732/176975604-9952b971-8379-4628-84b9-1fe274833d17.png)
![image](https://user-images.githubusercontent.com/94152732/176976098-43fdbc56-0d4b-4b98-82a9-bf1a2bd199d0.png)


- Step 2: Step 2 – Refactor Ansible code by importing other playbooks into site.yml
![image](https://user-images.githubusercontent.com/94152732/176976485-f7d82ba2-81fd-4c82-93e0-01603d301d2c.png)

- 1 : 
![image](https://user-images.githubusercontent.com/94152732/176976840-6a89168f-166a-420b-a10f-ae8219f1d843.png)

- 2: 
![image](https://user-images.githubusercontent.com/94152732/176977491-3e60a013-22f9-4a96-8d3e-cbff7b001bd8.png)

- 3: 
![image](https://user-images.githubusercontent.com/94152732/176977948-e3f73d93-20ec-4c39-b1e9-375af9b1d04a.png)

- 4: 
![image](https://user-images.githubusercontent.com/94152732/176978837-bf54c431-e7d9-47fb-94ce-4b05cb8e4fa8.png)


- 5: 

![image](https://user-images.githubusercontent.com/94152732/176978760-0029e0e6-2179-4dea-9294-7ce2537185ce.png)
![image](https://user-images.githubusercontent.com/94152732/176978926-e638f882-628a-4595-b3b8-20e8cd19cb08.png)
![image](https://user-images.githubusercontent.com/94152732/176979394-1fcb88ae-7331-49ed-80ee-dba949119784.png)
![image](https://user-images.githubusercontent.com/94152732/176980153-e2146401-0fb6-4bff-9236-d83ae6f1a3f6.png)
![image](https://user-images.githubusercontent.com/94152732/176980261-fef077ee-7df1-49fd-8cde-6c5e4c14676b.png)

- Step 3 – Configure UAT Webservers with a role ‘Webserver’

- 1: Launch 2 fresh EC2 instances
![image](https://user-images.githubusercontent.com/94152732/176999814-fdde4072-8d08-415b-ae63-17771c5112f6.png)

- 2: Roles Directory created
![image](https://user-images.githubusercontent.com/94152732/177000271-e14a8aae-6d4d-4be1-9fe9-30cde9ff2ddf.png)

-3:
![image](https://user-images.githubusercontent.com/94152732/177000445-ad1a5f85-d3d0-48d3-93ea-f27500b2eef3.png)

- 4: 
![image](https://user-images.githubusercontent.com/94152732/177001144-6070d90c-e4de-4eae-b26d-f99537a68429.png)

-5: 
![image](https://user-images.githubusercontent.com/94152732/177001434-a87ea7df-86ba-4dc3-937f-58d507dfbdf0.png)

- Step 4: Reference ‘Webserver’ role






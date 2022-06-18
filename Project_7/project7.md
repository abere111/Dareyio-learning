- Step 1

- 1: Spin up an EC2 instance
![image](https://user-images.githubusercontent.com/94152732/172205536-76f28add-5c78-4494-89a4-f901b99b79b3.png)

- Step 2

- 2: Attached Volume to the instance
![image](https://user-images.githubusercontent.com/94152732/172205631-da69a928-0cd5-42e6-ae5d-b6f4b7f1afe4.png)

- 3: lsblk command
![image](https://user-images.githubusercontent.com/94152732/172205963-8b5f4588-7e05-4750-a974-896d31d33f06.png)

- 4: df command
![image](https://user-images.githubusercontent.com/94152732/172206279-81e2de51-87e2-444e-a681-fb1462de6624.png)

- 5: gsdisk command to create single partitions
![image](https://user-images.githubusercontent.com/94152732/172208674-37570545-08e2-4fcc-8fc5-c4fc53f2a380.png)

- 6: Installing lvm2
![image](https://user-images.githubusercontent.com/94152732/172209081-013d1a6d-9a9a-4dc0-a905-38d6aad0d49f.png)
![image](https://user-images.githubusercontent.com/94152732/172209231-37c16101-67b9-4b22-88d9-473a659aceaa.png)


- 7: Using pvcreate
![image](https://user-images.githubusercontent.com/94152732/172209493-90dc604e-214b-43f9-b46f-9605bf869dc8.png)

- 8: Verify Physical Volume
![image](https://user-images.githubusercontent.com/94152732/172209722-6d6da676-4d01-4e86-86e0-0e70b681867e.png)

- 9: Adding PVs to VG
![image](https://user-images.githubusercontent.com/94152732/172210246-3eb10a2f-76da-4998-bce1-8df810a5ce82.png)

- 10: Veriified VG
![image](https://user-images.githubusercontent.com/94152732/172210421-d6fcbcee-aa1b-4f48-9095-6d6cb23a645f.png)


- Step 3

- 11: Created 3 LVs
![image](https://user-images.githubusercontent.com/94152732/172211034-44efc829-7b02-46c4-b95b-debbc962d46f.png)

- 12: LV created 
![image](https://user-images.githubusercontent.com/94152732/172211300-13146c1c-737d-47ae-95ca-ed55aadc0ae6.png)

- 13: Vderifioed the entire set up
![image](https://user-images.githubusercontent.com/94152732/172211556-4c6574f2-054e-4c77-b2bb-05f2029e4b31.png)
![image](https://user-images.githubusercontent.com/94152732/172211654-afa42138-deba-4ba1-af09-85b021555570.png)

- 14: Formatted the LVs using xfs
![image](https://user-images.githubusercontent.com/94152732/172212554-73fc2a88-c005-4eaa-b2b4-47b5aff6324d.png)

-15: Created mount points
![image](https://user-images.githubusercontent.com/94152732/172213124-bc754ae3-e5e5-4546-ae8b-c96035d9c3ea.png)

-16: Mounted the directories to LVs
![image](https://user-images.githubusercontent.com/94152732/172213977-12c72531-3e64-4f29-8fba-b817d8f22946.png)

- 17: Back up  /var/log into /home/recovery/logs/
![image](https://user-images.githubusercontent.com/94152732/172214624-b049fed5-2cba-42de-b627-75ea93d18b12.png)

- 18: Update Fstab
![image](https://user-images.githubusercontent.com/94152732/172667755-5eb3b72d-0b3c-451f-ba2f-211600057398.png)
![image](https://user-images.githubusercontent.com/94152732/172670162-3e1cc24c-2f25-4113-ac58-22daa74ee091.png)

- 19: Test Configuration and Reload daemon
![image](https://user-images.githubusercontent.com/94152732/172670255-5e4de1c2-958e-4dca-b7d4-2799520d6fa7.png)
![image](https://user-images.githubusercontent.com/94152732/172670609-24b74e6d-a3de-4418-aa55-343c6fcfb7ed.png)
![image](https://user-images.githubusercontent.com/94152732/172670780-d33c991d-8a65-47b2-9ee3-518ae2e39626.png)


Step 4:

- 20: Install NFS Server
![image](https://user-images.githubusercontent.com/94152732/172218401-3d057619-3845-4b12-9e87-cf37e485110d.png)
![image](https://user-images.githubusercontent.com/94152732/172218577-a675597e-a07f-4b80-9221-2ac89437dc6b.png)
![image](https://user-images.githubusercontent.com/94152732/172218940-4d49e6b7-9255-4fd3-bf4f-771d783d370d.png)

Step 5: 

- 21: Subnet CIDR
![image](https://user-images.githubusercontent.com/94152732/174421359-794d4938-b1f9-4a6e-852b-47248d26b0d6.png)
![image](https://user-images.githubusercontent.com/94152732/174421534-94262ebd-bd29-4821-b530-18d85466fcfe.png)

- 22: Configure Access to NFS
![image](https://user-images.githubusercontent.com/94152732/174421782-2fcf8db6-32e8-4cd8-97b4-e1f83c4a1879.png)
![image](https://user-images.githubusercontent.com/94152732/174421807-595bbe0f-1d62-4b92-a9dc-ad3ecc34b676.png)

Step 6:

- 23: Check which port is used by NFS and open it using Security Groups (add new Inbound Rule) 
![image](https://user-images.githubusercontent.com/94152732/174421902-4ce44295-2500-4bf1-a085-fc6b87fab8b7.png)
![image](https://user-images.githubusercontent.com/94152732/174422097-cb7e8ec2-f1a0-4662-a2b2-b2d6c66ed64b.png)
![image](https://user-images.githubusercontent.com/94152732/174422107-ef6d33e7-f51c-4ca0-a255-35c5ac337ec5.png)


- LAUCH A DATABSE SERVER

![image](https://user-images.githubusercontent.com/94152732/174422554-0509fa6b-9639-4441-b50a-6c54da0fe1db.png)
![image](https://user-images.githubusercontent.com/94152732/174422700-d15840f3-59e1-42c8-902f-f0c354bee65e.png)
![image](https://user-images.githubusercontent.com/94152732/174422822-065d5d21-2629-4a68-8a6e-3a4bd9cee06f.png)
![image](https://user-images.githubusercontent.com/94152732/174422888-02b158eb-35d2-4cfd-b9e9-1658ffd3b05d.png)
![image](https://user-images.githubusercontent.com/94152732/174422902-89029e37-0a50-49d4-bfa1-92b5100f3c2f.png)
![image](https://user-images.githubusercontent.com/94152732/174423132-3762f677-95bb-48a1-9f82-3d1283e3774e.png)

- 1. ![image](https://user-images.githubusercontent.com/94152732/174423485-6e7d8703-d82c-4540-ae29-dd19ab5edf27.png)
- 2. ![image](https://user-images.githubusercontent.com/94152732/174423588-05b5fd0d-d806-4665-887c-c9875fad0780.png)
- 3. ![image](https://user-images.githubusercontent.com/94152732/174423638-438e9486-01fd-4e96-96a9-ad3ce6a66eec.png)
- 4. ![image](https://user-images.githubusercontent.com/94152732/174423721-df41a2b3-bce0-4a55-a122-e7ac2523749a.png)
- 5. ![image](https://user-images.githubusercontent.com/94152732/174423766-8ae80f6a-eb24-4ce3-90ab-a65686b23d40.png)

- On WebServer 1
![image](https://user-images.githubusercontent.com/94152732/174423785-bbad941f-84a8-4552-890b-12fe3dfcd406.png)
![image](https://user-images.githubusercontent.com/94152732/174423824-c50de524-9cba-4bcc-9742-71309e90ffb8.png)
![image](https://user-images.githubusercontent.com/94152732/174423851-d3298846-c1a7-4196-b6cd-bc47e0a8af02.png)
![image](https://user-images.githubusercontent.com/94152732/174423891-7c971110-30cc-4abb-bb0c-260fe6b58bb7.png)
![image](https://user-images.githubusercontent.com/94152732/174423960-dc1a7973-652d-4353-9c13-22ab3342b421.png)
![image](https://user-images.githubusercontent.com/94152732/174424012-db2d2da8-070e-4e81-b699-6f349b7309de.png)
![image](https://user-images.githubusercontent.com/94152732/174425128-56b03d23-08e2-4e3f-b3d9-8b2fa795ee27.png)
![image](https://user-images.githubusercontent.com/94152732/174425155-8e433b67-c0d9-4072-b9c3-99aad97b64d8.png)
![image](https://user-images.githubusercontent.com/94152732/174425719-8c4e8ba4-603d-446b-8a5b-aa4e1d9fb8ea.png)
![image](https://user-images.githubusercontent.com/94152732/174425788-82b15e76-763b-439d-97eb-e6313bdec31b.png)
![image](https://user-images.githubusercontent.com/94152732/174425997-0e34ce56-57f2-47d7-a359-ad8b602e4962.png)
![image](https://user-images.githubusercontent.com/94152732/174426080-a93d16b5-bf50-42c5-a78b-e13334052f20.png)
![image](https://user-images.githubusercontent.com/94152732/174426397-6d9a20cf-dcb4-472f-b01c-76919c2a872f.png)
![image](https://user-images.githubusercontent.com/94152732/174426521-760dd614-aa6e-498e-b6e7-a530592db30a.png)
![image](https://user-images.githubusercontent.com/94152732/174427633-074057e7-2c2d-4d73-bab2-d2cc9823f78f.png)
![image](https://user-images.githubusercontent.com/94152732/174429135-7ba1cbdf-bf29-45ce-9218-2772be85a41b.png)
![image](https://user-images.githubusercontent.com/94152732/174429895-51f82877-c350-463f-8b80-7b4f435a5844.png)
![image](https://user-images.githubusercontent.com/94152732/174429905-37144743-b6ab-4570-9baa-206f6ae5743a.png)



- On WebServer 2

















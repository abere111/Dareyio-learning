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

Step 4:

- 18: Install NFS Server
![image](https://user-images.githubusercontent.com/94152732/172218401-3d057619-3845-4b12-9e87-cf37e485110d.png)
![image](https://user-images.githubusercontent.com/94152732/172218577-a675597e-a07f-4b80-9221-2ac89437dc6b.png)
![image](https://user-images.githubusercontent.com/94152732/172218940-4d49e6b7-9255-4fd3-bf4f-771d783d370d.png)














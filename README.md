# Hyper-V_secure_file_server
This is a simple file server that allows users to upload, download, and manage files over a network. It supports basic authentication and organizes files into directories for easy access. Ideal for personal projects or learning about server management.

# 1. create users
  * create a user account for myself
    * add users to administrators group
    * ![image](https://github.com/user-attachments/assets/e60e4979-2f63-4580-a317-855bb106a796)
    * ![image](https://github.com/user-attachments/assets/d0b642b0-1369-4a1b-a635-d78803745cbe)
    * ![image](https://github.com/user-attachments/assets/d4d78ffc-898c-4222-bf7d-77fc6dc586c2)

# 2. create groups
  * finance - adding user1
  * ![image](https://github.com/user-attachments/assets/ca65a3b2-b95a-4fa3-8201-3bc65cdcff5d)
  * ![image](https://github.com/user-attachments/assets/956f1603-6d59-47fb-9ca6-83efd14e7cd3)
  * ![image](https://github.com/user-attachments/assets/a14e7320-9535-4fac-86f5-ce936ca006da)
  * marketing - adding user2
  * ![image](https://github.com/user-attachments/assets/e78a1175-b3d0-49d8-b2e0-a1be16c54598)
  * ![image](https://github.com/user-attachments/assets/7a77f6f6-4ff0-421f-8dc9-8b207cf2d696)

# 3. create groups
  * create an E:\ Drive (2-4GB)
  * ![image](https://github.com/user-attachments/assets/cd9876c7-78a9-4939-a6a5-e47e1aa7391d)
  * ![image](https://github.com/user-attachments/assets/565968eb-8fa6-44c5-9028-1ddbfc502830)
  * ![image](https://github.com/user-attachments/assets/a7612bc5-5794-41f3-99be-4f24e60fcd01)
  * ![image](https://github.com/user-attachments/assets/67794018-288a-4863-b6f1-0842d30da37e)
  * ![image](https://github.com/user-attachments/assets/a88d0858-8a84-4727-ba43-735614ee7a93)
  * ![image](https://github.com/user-attachments/assets/77720c6c-202d-485f-9c7b-7c1054349479)
  * ![image](https://github.com/user-attachments/assets/6b5aa368-ab1d-414d-8d71-d65279ee1170)
  * ![image](https://github.com/user-attachments/assets/072168c5-7557-4952-82e0-a5a8bb02e9e7)
  * ![image](https://github.com/user-attachments/assets/d50df01b-67cf-4871-b3f2-387ff96e1dbf)
  * ![image](https://github.com/user-attachments/assets/c8f48ef1-8738-4d69-97c7-950798d760be)
  * ![image](https://github.com/user-attachments/assets/b8f7eafb-d136-4cdb-90af-34e6a3e9c4d9)
  * ![image](https://github.com/user-attachments/assets/b4293fda-e59e-4347-8eb5-dc796314d241)
  * ![image](https://github.com/user-attachments/assets/8330851d-27e4-465b-831a-7f51d2780203)
     - Edit the NTFS permissions:
       - giving my user account - Full control 
       - ![image](https://github.com/user-attachments/assets/54b60934-96a4-4679-bc95-86748ebe37f6)
       - ![image](https://github.com/user-attachments/assets/4458e072-cb79-4533-abd8-b6c93ec32c05)
       - ![image](https://github.com/user-attachments/assets/4f973490-2b57-4475-929d-f1540e98937d)
       - ![image](https://github.com/user-attachments/assets/0bf6d9f7-8d8c-4ea6-b736-b74b2a93e77d)
       - ![image](https://github.com/user-attachments/assets/3b22d58c-b9d4-4fbc-a9fd-0c3c6f457734)
       - ![image](https://github.com/user-attachments/assets/cdedef52-48ad-4654-baec-c7b562bd3774)
       - Giving the admin group - Full control
       - ![image](https://github.com/user-attachments/assets/e72012d7-1b21-4e59-aea3-be2e9f61a9bb)
       - Giving full control to user1 & user2 too
       - ![image](https://github.com/user-attachments/assets/7515e9c2-1532-432e-aa96-bb7ce1f4a663)
  * Create 4 folders in the root of E:\ (HOME, Company, Finance, and Marketing)
  * ![image](https://github.com/user-attachments/assets/3f71b4bd-0866-45e4-a64d-2c8eaf9b01a5)
  * ![image](https://github.com/user-attachments/assets/9de71599-b0ee-45d5-9a78-28ca4205349e)
  * ![image](https://github.com/user-attachments/assets/eab9caa5-f7f3-4017-ae5c-a9ec7eb097ef)
  * ![image](https://github.com/user-attachments/assets/1774262e-8d09-4aeb-9110-b53f7d881c76)
     - Edit the NTFS folder permissions:
       - E:\Company: give the Users group Read and Execute permissions.
       - ![image](https://github.com/user-attachments/assets/af2b63ae-be35-4ac2-94ad-379fd5e4fd52)
       - ![image](https://github.com/user-attachments/assets/3ea736d0-f58b-4799-8821-a35de336790a)
       - ![image](https://github.com/user-attachments/assets/685a1a31-9de9-4ba7-b547-1501ea50b151)
         as you can see the users already have read & execute on top of having full control, why? it's because they had full control permission on the E drive itself. now I will remove the those persmission of users on the E\ drive an
         <br>
         ![image](https://github.com/user-attachments/assets/9a6e89d1-bbb9-43cb-9286-ef42297844f7)
         ![image](https://github.com/user-attachments/assets/436d6c7e-8cb5-476d-aca6-c0b3d72aed6a)
         ![image](https://github.com/user-attachments/assets/056ae7ad-8270-44ee-937b-486fcfabdc58)
         ![image](https://github.com/user-attachments/assets/1f208545-8d4e-4b2e-9f17-74a60ce57a57)
         <br>
         now let's go back and see or give the read & execute to the users for 'company' folder
         <br>
         ![image](https://github.com/user-attachments/assets/607d4a71-907d-4133-a73c-4d413fbe2ba3)
         ![image](https://github.com/user-attachments/assets/61d882d7-fe4f-49d0-ac97-87b31265a855)
       - E:\Finance: give the Finance group Modify permissions.
       - ![image](https://github.com/user-attachments/assets/b68772d3-915d-40b0-9ea6-a2b7c69fdeb9)
       - ![image](https://github.com/user-attachments/assets/4c0070b0-5534-4014-94c0-8e7b7a2bd8bb)
       - ![image](https://github.com/user-attachments/assets/9f185210-09a8-4258-9aaf-e8bca14386ab)
       - E:\Marketing: give the Marketing group Modify permissions.
       - ![image](https://github.com/user-attachments/assets/340b4a30-69f4-4d1f-87d3-f685b90813f1)
       - ![image](https://github.com/user-attachments/assets/8fb8dc78-7348-41c1-bde6-2ec3327b541d)
       - ![image](https://github.com/user-attachments/assets/72ad5cac-bfd5-49f2-a490-946f4d304b9f)
 * Create 2 folders in E:\Home\ (user1, user2)
















































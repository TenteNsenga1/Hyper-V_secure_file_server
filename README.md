# Hyper-V_secure_file_server
This is a simple file server that allows users to upload, download, and manage files over a network. It supports basic authentication and organizes files into directories for easy access. Ideal for personal projects or learning about server management.

# Login to SRV 
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
   * ![image](https://github.com/user-attachments/assets/76d487ca-7b3f-4b65-af80-059a2d1f050f)
   * ![image](https://github.com/user-attachments/assets/7c492f05-2057-4a07-b3e3-976a7db3b714)
     - Edit the NTFS folder permissions
       - E:\Home\user1: give user1 Full Control
         - ![image](https://github.com/user-attachments/assets/0cf69574-1d8d-45df-8ea7-285656402405)
         - ![image](https://github.com/user-attachments/assets/c5a880d2-40de-4934-870a-0892eb48d662)
         - ![image](https://github.com/user-attachments/assets/4e9f3be8-bf2f-47ab-9d27-50db2699cb43)
         - ![image](https://github.com/user-attachments/assets/a952d301-822b-4fc5-9541-00609533da5b)
         - ![image](https://github.com/user-attachments/assets/70759d90-e5e6-4d76-8016-ac5816a198ea)
         - ![image](https://github.com/user-attachments/assets/cfa998a6-4bcd-41e7-82a6-26191d77aeaf)
       - E:\Home\user1: give user1 Full Control
         - ![image](https://github.com/user-attachments/assets/cb8347bc-66c5-45f4-b008-7ebb7ed99aaa)
         - ![image](https://github.com/user-attachments/assets/2cbc0d4e-28e7-45ed-a9b4-452c46762586)
  * share folders
    - Permissions: everyone full control
    - Share Names
      - E:\Company: Office
        - ![image](https://github.com/user-attachments/assets/df692d1f-6d12-4365-91a3-b83de32e6da6)
        - ![image](https://github.com/user-attachments/assets/0e6b5cda-08c0-4d68-9140-f2459698a25d)
        - ![image](https://github.com/user-attachments/assets/1254887e-95cb-4f26-8f39-8adbd8e795cd)
        - ![image](https://github.com/user-attachments/assets/dc236afb-74fc-430d-803f-a1531e863613)
        - ![image](https://github.com/user-attachments/assets/05d6244d-43ee-4105-9956-2827674c5c7c)
        - ![image](https://github.com/user-attachments/assets/d594489b-910a-4d95-bea1-3c81eea1b0a7)
        - ![image](https://github.com/user-attachments/assets/816fa734-9c25-4a1b-9ce4-fad65792f244)
      - E:\Finance: Finance
        - ![image](https://github.com/user-attachments/assets/954a8a61-218e-4bf8-ad10-682d98e78b6a)
        - ![image](https://github.com/user-attachments/assets/044fe693-eb11-4109-bb4a-d9bf9c419f8d)
      - E:\Marketing: Marketing
        - ![image](https://github.com/user-attachments/assets/79e5b6a4-f948-4b6b-ac21-f99cb7d90640)
        - ![image](https://github.com/user-attachments/assets/2631d679-3e40-4921-9363-5d68b2a786d6)
        - ![image](https://github.com/user-attachments/assets/effc9e3b-79ca-4625-9cbf-dd642db33f3f)
        - ![image](https://github.com/user-attachments/assets/aca36f9b-7558-4c12-8d07-ef1a3da44d15)
        - ![image](https://github.com/user-attachments/assets/44f3b9db-7893-4c2a-b54e-99278c3c3ba1)
      - E:\Home: Home
        - ![image](https://github.com/user-attachments/assets/3cc838d4-43a0-462d-acfd-c4523d04b90b)
        - ![image](https://github.com/user-attachments/assets/74c51732-b1b7-414c-a7ec-0e22f56a3759)
        - ![image](https://github.com/user-attachments/assets/067742f2-5b21-4687-858e-b0d563381c0e)
        - ![image](https://github.com/user-attachments/assets/83c663ad-5326-4816-b2d7-90f4e1175806)
        - ![image](https://github.com/user-attachments/assets/078cbf79-5851-4820-880f-ebc3effdec67)
        - ![image](https://github.com/user-attachments/assets/6a4653f6-cd5f-4e2a-bb7b-dcba41c06c5d)
        - ![image](https://github.com/user-attachments/assets/12977a9d-d8c4-4916-ad94-5c4919765686)
        - ![image](https://github.com/user-attachments/assets/cb65eeeb-f69b-4d08-9809-303f38a0db05)
        - ![image](https://github.com/user-attachments/assets/97935a35-1ee8-49b9-bd85-488f6a5f093c)

# Login to both PCs and Map Network Drives
  * 1. On PC-01, mapping 3 drives using the folowing commands:
        - Home Folder: net use h: \\srv\Home$\user1 /persistent:yes


















































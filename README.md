# IMplementing-Traffic-Management-via-LB-App-gateway-Hub-Spoke

## In this lab, we will handle:

-- Provision the lab environment
-- Configure the hub and spoke network topology
-- Test transitivity of virtual network peering
-- Configure routing in the hub and spoke topology
-- Implement Azure Load Balancer
-- Implement Azure Application Gateway

Architecture Diagram

![ArchitectureDiagram](https://user-images.githubusercontent.com/121365233/223602419-6efaffdc-1fcb-4b06-b507-b939e1da4ff4.png)

1) Create 3 different resource groups.

2) Create 3 seperate Vnets+ 5 subnets(3 in Vnet1 (1 is for appgw. I have created this one later additionally ), 1 in Vnet2, 1 in Vnet3,) in resource group 1.

![Screenshot 2023-03-07 at 3 26 45 PM](https://user-images.githubusercontent.com/121365233/223544749-9901b35e-1395-4982-ae8e-883587d3d3c5.png)
![Screenshot 2023-03-07 at 3 29 39 PM](https://user-images.githubusercontent.com/121365233/223545315-4118edf4-864a-4d52-a171-96a09d140e6a.png)

2.1 Run the given comment in terminal to deploy your script.

![Screenshot 2023-03-07 at 3 34 50 PM](https://user-images.githubusercontent.com/121365233/223546598-b8247fba-e024-48f3-b440-a4c0b7a658c6.png)

3) Configure peering. (whether by peering or Hub and Spoke)

![Screenshot 2023-03-07 at 6 29 48 PM](https://user-images.githubusercontent.com/121365233/223604425-73fe72f4-534b-4662-99f5-78d9dad7a504.png)

![Screenshot 2023-03-07 at 6 35 59 PM](https://user-images.githubusercontent.com/121365233/223604463-7ba42447-2e19-4140-a226-d8706e1d8a3b.png)

![Screenshot 2023-03-07 at 6 40 58 PM](https://user-images.githubusercontent.com/121365233/223604508-ceb90a86-f483-41a4-b471-713670f81ebe.png)

![Screenshot 2023-03-07 at 6 42 21 PM](https://user-images.githubusercontent.com/121365233/223604537-9d9efc91-4322-4616-892c-95fe2bd59f2d.png)

![Screenshot 2023-03-07 at 6 47 08 PM](https://user-images.githubusercontent.com/121365233/223604621-bc06574c-d2e4-4c15-a69c-cd7296e82569.png)

4) Test transitivity of virtual network peering.

![Screenshot 2023-03-07 at 7 48 38 PM](https://user-images.githubusercontent.com/121365233/223605071-95543879-9b86-45d2-9468-714f00ed6fb6.png)

![Screenshot 2023-03-07 at 8 34 44 PM](https://user-images.githubusercontent.com/121365233/223605221-522560c7-cac5-4d87-8a63-e1fff1dd88b1.png)

5) Configure routing in the hub and spoke topology

![Screenshot 2023-03-07 at 8 20 57 PM](https://user-images.githubusercontent.com/121365233/223605844-14fbd971-7961-4962-96d5-ea52fced576d.png)

![Screenshot 2023-03-07 at 8 22 22 PM](https://user-images.githubusercontent.com/121365233/223605862-88281d2c-f782-44bf-b558-4bc887037d28.png)

![Screenshot 2023-03-07 at 8 29 25 PM](https://user-images.githubusercontent.com/121365233/223605892-d5466ccd-7070-4049-977d-e042d62cacb8.png)

6) Implement Azure Load Balancer

![create load balancer](https://user-images.githubusercontent.com/121365233/223606443-4a92faa4-b492-44ad-9b4e-7cd85bf5d269.png)

![Screenshot 2023-03-07 at 7 29 19 PM](https://user-images.githubusercontent.com/121365233/223606461-43580162-d669-4272-8901-aba516666b97.png)

![Screenshot 2023-03-07 at 7 31 55 PM](https://user-images.githubusercontent.com/121365233/223606478-2b764b60-9529-4d5d-9877-0ba8dca89728.png)

![Screenshot 2023-03-07 at 7 35 44 PM](https://user-images.githubusercontent.com/121365233/223606496-a07e2a34-64b4-436e-8036-569233c7383d.png)

![Screenshot 2023-03-07 at 7 38 55 PM](https://user-images.githubusercontent.com/121365233/223606520-baecd1f9-2cf0-42e8-830d-ff24a5b3d950.png)

7) Implement Azure Application Gateway

![Screenshot 2023-03-07 at 8 39 25 PM](https://user-images.githubusercontent.com/121365233/223606706-e3f8c5b0-625a-4d89-8acd-456aaf162008.png)

![Screenshot 2023-03-07 at 8 59 36 PM](https://user-images.githubusercontent.com/121365233/223606738-0d7fac73-8bad-45de-ba2a-bae39a85882a.png)

TOPOLOGY

![Screenshot 2023-03-07 at 9 13 42 PM](https://user-images.githubusercontent.com/121365233/223602263-d06a44ee-34b5-42fd-880b-020d61e621ab.png)


<h1>How to Create VMs in Azure</h1>
This tutorial will supplement the "create VMs step" in all of my other projects. There will be slight variations in the VMs based on the project but the overall process is the same.

<h1>Steps</h1>
<p>
<img width="1907" height="998" alt="image" src="https://github.com/user-attachments/assets/e4ed221a-076b-40d6-b16f-baaca4ea1497" />
</p>
<p>
Navigate to Azure homepage, I created a free account with available credits
</p>
<br />

<p>
<img width="1914" height="913" alt="image" src="https://github.com/user-attachments/assets/02a0fbfb-fb21-4c98-8ed6-879822eb24bb" />
</p>
<p>
Navigate to the Virtual Machines page on the homepage.
</p>
<br />

<p>
<img width="1913" height="916" alt="image" src="https://github.com/user-attachments/assets/280aa8e1-7c63-4c1a-9409-b6e5856c2372" />
</p>
<p>
Click the "Create" tab and select "Virtual machine."
</p>
<br />

<p>
<img width="842" height="481" alt="image" src="https://github.com/user-attachments/assets/a8f23076-0751-4726-aeae-09fb944fdf58" />
</p>
<p>
In the project details section, use the current subscription and select "Create new" for resource group. The resource group will house this VM.
(Note: Since I created a new resource group within the VM creation page, the resource group will automatically be in the same region as the VM)
</p>
<br />

<p>
<img width="823" height="601" alt="image" src="https://github.com/user-attachments/assets/6fdea280-6bdf-4e61-8bf3-6f6813728d4b" />
</p>
<p>
In the Instance details section, name the VM and select the region.(Note that the resource group and VM need to be in the same region). Select the OS image for the VM.
</p>

<p>
<img width="823" height="601" alt="image" src="https://github.com/user-attachments/assets/6fdea280-6bdf-4e61-8bf3-6f6813728d4b" />
</p>
<p>
In the Instance details section, name the VM and select the region.(Note that the resource group and VM need to be in the same region). Select the OS image for the VM.
</p>

<p>
<img width="785" height="734" alt="image" src="https://github.com/user-attachments/assets/688352fb-7143-4c3e-9882-b747099099ba" />
</p>
<p>
In the Instance details section, select the size, create a username and password, and check the licensing agreement option.
</p>

<p>
<img width="1905" height="868" alt="image" src="https://github.com/user-attachments/assets/3fc9ac31-49d3-4e37-9150-b79a71346216" />
</p>
<p>
Scroll back to the top of the page and select the "Networking" tab.
</p>

<p>
<img width="1912" height="870" alt="image" src="https://github.com/user-attachments/assets/89246d00-e402-42ad-8322-862cc0128405" />

</p>
<p>
In the Networking tab, the virtual network and subnet should automatically populate. For Public IP, select "create new", and name the public IP. Select "Review + create".
</p>

<p>
<img width="1905" height="866" alt="image" src="https://github.com/user-attachments/assets/51ca200f-6084-4012-961b-f424f054046f" />
</p>
<p>
In the "Review + create" tab, select create. Azure will do a validation check to make sure the VM requirements are valid.
</p>

<p>
<img width="1905" height="866" alt="image" src="https://github.com/user-attachments/assets/51ca200f-6084-4012-961b-f424f054046f" />
</p>
<p>
In the "Review + create" tab, select create. Azure will do a validation check to make sure the VM requirements are valid.
</p>

<p>
<img width="1913" height="910" alt="image" src="https://github.com/user-attachments/assets/0072da66-4cba-43c7-877d-788676746059" />
</p>
<p>
Navigate back to the Virtual Machines tab from Azure sidebar to see that the VM was created and given a random public IP address.
</p>

<p>
<img width="406" height="243" alt="image" src="https://github.com/user-attachments/assets/43d72107-5552-4784-a6f5-d3187c837e58" />
</p>
<p>
Navigate to Remote Desktop Connection and type in the public IP address from the VM-demo machine and select connect.
</p>

<p>
<img width="452" height="583" alt="image" src="https://github.com/user-attachments/assets/bc5832cc-b163-4b84-8704-c712f52f2a4d" />
</p>
<p>
Enter username and password that was used when creating the VM and select OK.
</p>

<p>
<img width="1915" height="1079" alt="image" src="https://github.com/user-attachments/assets/f4a9bccd-d0a9-4d2c-b577-a7c5aeff7013" />
</p>
<p>
Successfully logged into the VM with the credentials "labuser".
</p>






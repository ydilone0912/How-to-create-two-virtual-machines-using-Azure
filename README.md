<p align="center">


<h1> How-to-create-two-virtual-machines-running-in-same-network-using-Azure</h1>


<img src="https://i.imgur.com/tsoRjEI.png" alt="Traffic Examination"/>
</p>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2>Actions and Observations</h2>


Actions:

1- Log in to the Azure Portal (https://portal.azure.com/).

2- Click on the "Create a resource" button in the upper-left corner of the portal.

3- In the search bar, type "Virtual machine" and select "Virtual machine" from the list of suggestions.

4- Click the "Create" button to start the process of creating a virtual machine.

5- Choose the subscription and resource group in which you want to create the virtual machines.

6- Give your first virtual machine a name and select the region where it will be hosted.

7- Choose the operating system and image you want to use for the virtual machine.

8- Specify the size of the virtual machine and the number of virtual CPUs and RAM you want to allocate.

9- Set up the virtual network and subnet for the virtual machine.

10- Choose whether you want to use managed disks or unmanaged disks for the virtual machine's storage.

11- Set up any additional features you need, such as availability sets or load balancers.

12- Review your settings and click the "Create" button to create the first virtual machine.

13- Repeat steps 6-12 to create the second virtual machine, making sure to use the same virtual network and subnet as the first virtual machine.

14- Once both virtual machines are created, go to the virtual network in the Azure Portal and create a new network security group.

15- In the new network security group, create inbound and outbound rules to allow traffic between the virtual machines.

16- Assign the network security group to both virtual machines.

17- Finally, you can connect to the virtual machines using Remote Desktop (for Windows) or SSH (for Linux) and verify that they are communicating with each other.


Observations:

By following these steps, you will have successfully created two virtual machines running in the same network using Azure as you can see in the image bellow.



<img src="https://i.imgur.com/VJ56o1v.png" alt="Traffic Examination"/>
</p>



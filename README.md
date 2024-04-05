# The Limitless Blue: Azure Beginner's Tutorial 📖
A Beginner's Tutorial to Microsoft Azure

<h2>Expectations 🤔</h2>
-Set Up Your Free Azure Subscription

-Gain a basic understanding of 3 core services provided by Azure:

  - Resource Groups
  - Storage Accounts
  - Virtual Machines

-Use the 3 services to create one of each.

<h2>What is Azure? ☁</h2>
Azure is a cloud computing service provided by Microsoft. It is a prominent cloud provider along with Amazon Web Services, Google Cloud Provider, Oracle Cloud Infrastructure, and IBM Cloud. Uses for Azure can include website hosting, storage and backup, media streaming, mobile app development, game development/hosting, and more.

<h2>Account Set-Up 🏗</h2>
<h3>Things You Will Need:</h3>
-Computer w/ Internet Connection

-Credit Card (Required for Free Azure Credits)

  - *Note: When your free subscription credits are out, Azure will not charge your card until you permit it to do so.*

Step 1: Go to www.Portal.Azure.com

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/6d1c058c-9dad-43e3-ac68-fe42104de6f7)

Step 2: Follow the Prompts and create your account with a credit card and email. 
  - You will have 30 days to use up your $200 of Azure Credits

Once you are logged in, you will see the Azure services available for use.

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/9bc3fbfd-4b28-4320-89e1-06b8fcc8a36a)

*You can take the prompted tour, otherwise, continue.*

<h2>Resource Groups 📚</h2>

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/e90d690e-6d00-4bd3-98e4-ba9a656903f2)

<h4>What is a Resource Group?</h4> 
A resource group in Azure is a container for organizing and managing related Azure resources, It serves as a boundary for management, access control, billing, and lifecycle management of resources within a solution, application, or project. 

<h3>Creating Your First Resource Group</h3>

Step 1: Click into "Resource Groups" under Azure services (or you can search it in the search bar above). You will come to the following screen.

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/812b59f4-214a-4fb5-867d-3de99e5cc966)

Step 2: Click Create in the upper left-hand corner.

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/daa8f786-4746-496e-9840-2fc12c5f238f)


Step 3: Name the Resource Group and choose the region. And click "Review + create" at the bottom.

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/618bedbe-b74f-4f06-8d70-d85052d8dbfc)
![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/d528129b-66fa-4cec-aee7-7b057a8721cf)


*If you hit Next: Tags, you can observe and place a tag of your own, however, we will not be specifying any Tags for this. Tags are used for additional organization inside the resource group such as naming the creators of a certain files within the group.*

Step 4: After you're done reviewing, hit "Create" again at the bottom of the screen to create the Resource Group. You should now see your newly created Resource Group on the list. 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/192db9a1-be95-4661-b819-e151831b4b52)

<h2>Storage Accounts 📦</h2>

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/ea14fcd2-0250-4bcd-9c59-6a85e9e07c51)

<h4>What is a Storage Account?</h4>
A storage account in Azure is a service that provides a scalable and secure location to store data in the cloud. It offers various types of storage, including blob, file, table, and queue storage, and can be accessed from anywhere over the internet. 

<h3>Creating Your First Storage Account</h3>

Step 1: On the Home Screen, Click Storage Accounts under Azure Services. 

Step 2: Click "Create" in the top left-hand corner of the screen

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/6b4eb25b-d6c1-4425-8283-e00698b95a54)

Step 3: Pick the Resource Group (You can use the Resource Group you created in the previous steps) and name the Storage Account. Everything else can be left at default for now.  

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/523e3e77-4668-4f74-b564-09074775c867)

*You can look around additional options by hitting "Next" but these options can also be left at default.*

Step 4: Review, Create and wait for it to Deploy.

Once the Storage Account is created, you can return to Storage Accounts and click into your newly made account. You can upload any files you may want to store. You may store text documents and other files.

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/2e2307d1-6aaf-47b5-aee0-87eac237a293)

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/4f933220-791a-4483-bf8e-2ab349ce1929)

<h2>Virtual Machines 🖥 </h2>

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/2901714a-92f9-40b4-a1f1-48f6615d2ca8)

<h4>What is a Virtual Machine?</h4>
A virtual machine is a software-based emulation of a physical computer that operates within another computer environment. It allows users to run multiple operating systems or applications on a single physical machine known as the host machine.

<h3>Creating Your First Virtual Machine</h3>

Step 1: From the Azure Home Screen, click on Virtual Machines under Azure Services and click create. You'll notice a Drop Down box. Click on the top option, "Azure Virtual Machine"

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/597802cb-9809-446b-ac64-39a434160f85)

Step 2: Pick a Resource Group (Again, you may use the same resource group you created in the previous steps) and name your machine. 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/0b73d6d0-c207-4406-89f1-3ee495155dab)

Step 3: Scroll down to "Image" and pick your OS. For this tutorial, we will be using Windows 10 Pro, version 22h2 - x64 Gen 2. 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/08e17aab-33d3-438d-b636-c4721dc6b0c4)

Step 4: Pick the "Size." This will be the vcpus and GiB memory your VM will be using. Picking a size of at least 2 vcpus is recommended. 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/43d7abff-1866-47e9-9445-2aa88a62b538)

Step 5: Create an Admin account and password for your VM. Don't forget your Admin and Password!

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/963a8346-ec54-4ccf-a821-17d9038fd3d4)

Step 6: Licensing and Creation. Make sure the Licensing box is checked and hit Review + create. Review your options if you need to and hit Create at the bottom and wait for the VM to deploy. 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/f98fec13-c430-4481-b217-da5fe433ef6a)

<h2>Connecting To Your New Virtual Machine 📲</h2>
Once your VM has deployed, you can now find it by returning to the Azure Home screen and clicking Virtual Machines. 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/81662b10-523f-43ea-bd06-e5a1ae58fb1f)

Step 1: To connect to the VM, first open your start menu and search for "Remote Desktop Connection" and click. 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/9e226fae-e70b-41c3-b7d7-601fd1f2acd3)

Step 2: A Public IP is needed so return to your Azure window and click into your VM. You'll see all the "Essentials" of your VM where you can also find the Public IP address. Copy the Address into your Remote Desktop Connection and Connect.

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/66fec2a1-d479-48c7-b260-33364d91db24)

Step 3: Login using the Admin account and Password you created while creating the VM. 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/6264c005-62df-4213-8485-6f0599ec1ac3)

Step 4: You may see the following screen: 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/51932f5d-a45e-4e87-b8df-60f3d96038fb)

This is because the "Size" you picked earlier may be outdated. However, for practice, this is not an issue. Hit Yes and observe the connection to your new VM. 

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/9a6c7726-6680-43e2-acd0-e6a4b3487ea1)

From here you, can explore this newly born VM. You can download things to it, store files or whatever else you please with it. 

<h2>Clean-Up 🧹</h2>

To prevent going through the free Azure credits too fast, it's recommended to delete the resource groups you made during this tutorial. This will in turn delete everything else inside including any storage accounts and VMs you made have created. 

Step 1: Return to Resource Groups. You may notice there's another resource group you haven't created. "NetworkWatcherRG"

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/6f6484ae-7d98-4a24-adfa-da4051efba60)

This RG gets created when you create a VM. Click onto NetworkWatcherRG and hit Delete Resource Group.

![image](https://github.com/EMoniSmall/azurecrashcourse/assets/166156618/f82eb33f-1f88-4b66-bc20-fa0398736438)

Follow the prompts and confirm the deletion. 

Step 2: Retun to resource groups again and now click into the Resource Group you created. Repeat the previous step and confirm the deletion of your resource group. 

*Note: Before deletion, you can observe all the files in the RG that were created by the VM*

Once both resource groups are deleted, you are now finished with the tutorial! 

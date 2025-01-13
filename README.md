# Azure VM Creation

This guide demonstrates the step-by-step process of creating a Virtual Machine in Azure.

---

## **Objectives**
1. Create a resource group.
2. Deploy a virtual machine.
3. Terminate the resources when finished.

---

## **Steps**

### A. Create a Resource Group
1. Open the Azure management console at [Azure Portal](https://portal.azure.com/?quickstart=True#home) (sign in with your account).
2. In the Azure search bar, search for "Resource groups" and select it.
3. Click on **Create** and fill in the following details:
   - **Subscription:** Free Trial or Pay-As-You-Go.
   - **Resource group name:** Provide a name of your choice.
   - **Region:** Leave as default (e.g., East US).
4. Click **Review + Create**, and then **Create**.

---

### B. Deploy a Virtual Machine
1. In the Azure search bar, search for "Virtual machines" and select it.
2. Click on **Create** and provide the following details:
   - **Subscription:** Free Trial or Pay-As-You-Go.
   - **Resource Group:** Select the one created earlier.
   - **Virtual Machine Name:** Provide a unique name.
   - **Region:** Select East US.
   - **Availability options:** Availability zone.
   - **Zone:** Select Zone 1.
   - **Image:** Ubuntu Server 22.04 LTS.
   - **Size:** Standard_B1s.
   - **Authentication type:** SSH key pair.
   - **Username:** azureuser.
   - **Public Inbound Ports:** Allow selected ports.
   - **Inbound Port:** SSH (22).
3. Use default options for:
   - **Disks**, **Networking**, **Management**, **Monitoring**, **Advanced**, and **Tags**.
4. Click **Review + Create**, and then **Create**.

---

### C. Terminate the Resources
1. In the Azure search bar, search for "Resource groups."
2. Select the resource group you created.
3. Click **Delete Resource Group** at the top.
4. Enter the resource group name to confirm.
5. Click **Delete**.

---

## **Note**
Ensure to delete the resources after completing the activity to avoid unnecessary charges.

---



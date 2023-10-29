# Project Title

This project demonstrates the integration of Azure Blob Storage, MATLAB, and OPC UA with Node-RED for real-time power consumption forecasting. The project includes the uploading of power consumption data into Azure Blob Storage and subsequently loading the data into MATLAB for forecasting.

## Setup Instructions

### Step 1: Setting up Azure Blob Storage and Accessing Data from MATLAB

1. **Create Azure Account:** Sign up for a Microsoft Azure account if you don't have one.
2. **Create Storage Account:** Create a new storage account in the Azure portal.
3. **Set up Blob Container:** Inside the created storage account, create a Blob container to store the power consumption data.
4. **Generate Access Keys:** Obtain the access keys for the storage account to authenticate the data upload.
5. **Configure Storage Access:** Configure the necessary permissions and access control for the Blob container.

6. **Access Data from MATLAB:** Utilize the Azure Storage SDK for MATLAB to access the uploaded data from the Azure Blob Storage. Implement the necessary code to load the data into MATLAB for further processing.

   ![Azure](step1.png)
   ![Azure to MATLAB ](matlabtoopcua.png)





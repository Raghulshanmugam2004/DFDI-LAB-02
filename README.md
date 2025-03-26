![Screenshot (95)](https://github.com/user-attachments/assets/65e926e1-b4cf-4b83-b217-58a679f296d4)# File Recovery using Autopsy

```
Register Number : 212222040128
Name : Raghul.S
```
## AIM:

This experiment aims to demonstrate:

- Create a **Disk Partition**.  

- Adding, deleting, and recovering files using Autopsy.

- Understanding the forensic recovery of deleted data.

- Removing the disk partition after the process.

## Step1:Create a New Disk
  
- The new Disk Partition is created as **Raghul**.
![Screenshot (87)](https://github.com/user-attachments/assets/a8b42260-1f1b-4ab0-b1d1-ebe52c895640)



## Step2: Adding and Deleting Files for Recovery

## 1. Copy Files to the Partition:

- Open File Explorer → Navigate to the newly created drive (C: or D:).

- Transfer images or files into it.
![Screenshot (88)](https://github.com/user-attachments/assets/758d8727-9ce5-4c78-a1c3-447d12637332)




## 2. Delete Files:

- Select one or more files → Press Delete.

- Empty the Recycle Bin to permanently remove them.

## Step3: Recovering Deleted Files Using Autopsy

## 1.Launch Autopsy and Set Up a New Case:

- Run Autopsy as Administrator.

- Click Create New Case.
![Screenshot (89)](https://github.com/user-attachments/assets/d1b8f463-1e8d-4637-acd4-44de4af9024e)


- Enter a case name (e.g., Autopsy1).
- Select a location for the case folder → Click Next → Finish.
![Screenshot (90)](https://github.com/user-attachments/assets/423cc0da-de63-4c6b-b072-adcc96a41d10)

- Add optional information
 ![Screenshot (91)](https://github.com/user-attachments/assets/28a418e8-b9cf-4fbf-9330-6a331379fe95)




## 2.Add the Partition as Evidence:

- Click Add Data Source → Choose Host.
   ![Screenshot 2025-03-19 223322](https://github.com/user-attachments/assets/3ad0612b-655b-406c-ab63-95912238b112)


- Select Local Disk → Click Next.
 ![Screenshot (92)](https://github.com/user-attachments/assets/dd222e30-d3e5-4863-beb5-9f0f624f6bf5)



- Choose Disk → Select the VHD drive (Drive1).
![Screenshot (93)](https://github.com/user-attachments/assets/ce41e437-443e-4f24-83bf-739e26a6b80a)



- Click Next → Keep the default settings → Click Finish.
  ![Screenshot 2025-03-19 224106](https://github.com/user-attachments/assets/3feb68c2-3a3a-4e21-b3b8-11f4dfac0990)


- Allow Autopsy to process the disk.

## 3.Extract Deleted Files:

- In the left panel, navigate to File Views → Deleted Files.

- Locate your deleted images.
![Screenshot (94)](https://github.com/user-attachments/assets/87050500-6102-4c17-a86a-a58d15dd705b)



- Right-click an image → Click Extract File.
![Screenshot (95)](https://github.com/user-attachments/assets/5e7767ad-ce9d-4547-a140-ad04fdfdae26)



- Choose a folder for saving the recovered files (e.g., C:\image_recovery).

- The deleted images are now restored!
![Screenshot (96)](https://github.com/user-attachments/assets/8eed22f9-b923-4227-aa42-4973107f487b)

- Check the disk.
![Screenshot (97)](https://github.com/user-attachments/assets/32c02eb2-199d-4950-bfc4-242563c64148)

  
## Step 4: Removing the Disk Partition (Optional Cleanup)

## 1.Using Disk Management:

- Open Disk Management (Win + X → Disk Management).

- Identify the created partition.

- Right-click on the partition → Select Delete Volume.

## 2.Alternative Method via Settings:

- Click the Start button → Go to Settings.

- Select System → Click Storage.

- Click Advanced Storage Settings → Select Disks & Volumes.

- View the list of available disks.

- Select the created partition → Click Properties.

- Click the Delete option to remove it.

## Result:

This experiment successfully demonstrates the creation of a disk partition, the deletion and recovery of files using Autopsy, and the proper removal of the partition after completing the process.


  

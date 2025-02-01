# OpenVaultFiles
The repository to store posts on OpenVault! Follow these instructions to make a post yourself. <br>
Visit OpenVault [here](https://open-vault-phi.vercel.app/).

## **1\. Accessing the Repository**

To contribute to **OpenVault**, visit the [Official OpenVaultFiles GitHub Repository](https://github.com/AlpineRobotics25710/OpenVaultFiles). 

## **2\. Forking the Repository**

Instead of cloning the repository, you should fork it. Forking creates a copy of the repository under your GitHub account, allowing you to make changes independently.

**Steps to Fork the Repository:**

1. Go to the [Official OpenVault GitHub Repository](https://github.com/AlpineRobotics25710/OpenVaultFiles).  
2. Click on the **Fork** button at the top-right corner of the page.  
3. Wait for GitHub to create a fork under your account.

**Video Guide:** [How to Fork a Repository](https://www.youtube.com/watch?v=07quEzZ-sJE)

## **3\. Adding a Folder for Your Contribution**

Once you've forked the repository, you can add your files directly through GitHub. **But first**, we have to **create a folder for your files**.

### **Creating a Folder for Your Contribution:**

1. Navigate to the appropriate folder in your forked repository (e.g., `ftc/cad/drivetrains/`).  
2. Create a folder following this naming structure: “YourTeam\#-NameOfContribution”  
   1. To create a new folder:  
      1. Click **Add File \> Create New File**.  
      2. Then in the new text box that appears, type the folder name and then “/”  
      3. E.g. 25710-SamplePost/  
3. Click **Commit Changes** to save.

## **4\. Add Your Files to Your Contribution Folder**

### **Required Files:**

**Each contribution** should have a **folder** containing:

1. An **`info.json`** file with metadata.  
2. A **preview image** (`.png` file) named as specified in **`info.json`**.

### **Adding your info.json file:**

On the same page that you created your folder, and in the same text box that you created your folder with:

1. Type “info.json” to create your **`info.json`** file.  
2. Copy and modify the corresponding template for CAD, Code, or Portfolio contributions:  
   **CAD contributions** should follow this **`info.json`** file format:

```javascript
{
   "preview-image-name": "your-preview-image.png",
   "title": "Your Drivetrain Title",
   "author": "Your Name",
   "description": "Describe your drivetrain, including unique features.",
   "used-in-comp": true if used in competition otherwise false,
   "team-number": "Your Team Number",
   "years-used": "Year(s) Used",
   "onshape-link": "Link to you CAD model on Onshape"
}
```

   **Code contributions** should follow this **`info.json`** file format:

```javascript
{
   "preview-image-name": "your-image-file-name.png",
   "download-name": "name of your file.zip",
   "title": "title of your code contribution",
   "author": "your name or you team's name",
   "description": "description of your code contribution",
   "used-in-comp": true if used in competition otherwise false,
   "team-number": "your team number",
   "years-used": "years you used it",
   "language": "languages-used"
}
```

   **Portfolio contributions** should follow this **`info.json`** file format:

```javascript
{
   "preview-image-name": "your-image-file-name.png",
   "file-name": "name of portfolio-file.pdf",
   "title": "name of your portfolio-submission",
   "author": "your name or you team's name",
   "description": "description of your portfolio submission",
   "team-number": "your team number",
   "years-used": "years you used it",
   "awards-won": "awards this portfolio won"
}
```

3. Click **Commit Changes** to save.

### **Uploading the Preview Image**

1. In the same folder, click **Add File \> Upload File**.  
2. Upload your **PNG preview image** (named exactly as in `info.json`).  
3. Click **Commit Changes** to save.
<p>
   <strong>Important Note:</strong>
   Your preview image and other download names for portfolio and code contributions should match the name of the
   corresponding files in your info.json file, otherwise the files will not be found.
   For the "used-in-comp" field, you must put either "true" or "false". There cannot be any quotations around the
   "true" or "false".
</p>

**4\. Example File Structure**

Great, now your submission should be ready, **but** just make sure to check that your contribution follows this file format:

```
ftc/
 ├── section(e.g. cad, code, portfolio)/
 │   ├── subsection-name(e.g. drivetrains, arms, auton, etc.)/
 │   │   ├── your-folder-name/
 │   │   │   ├── info.json
 │   │   │   ├── your-image(reminder: same as in JSON file).png
```

## **5\. Submitting a Pull Request**

Once you've added your files, submit a **Pull Request (PR)** to merge your changes into the main repository.

### **Steps to Create a Pull Request:**

1. Go to your forked repository.  
2. Click **Contribute \> Open Pull Request**.  
3. Add a title and description explaining your changes/contribution(doesn’t need to be too in depth, just make sure to add the name of your contribution folder somewhere so we can review it\!\!).  
4. Click **Create Pull Request**.

**Video Guide:** [How to Make a Pull Request](https://www.youtube.com/watch?v=nCKdihvneS0)

## **6\. Review & Approval**

Once you submit a pull request, maintainers will review it. If changes are needed, they'll provide feedback. Once approved, your contribution will be merged into **OpenVault**\!   
**Thank you** for contributing to the FTC robotics community\!

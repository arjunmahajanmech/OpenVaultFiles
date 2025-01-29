# OpenVaultFiles
The repository to store posts on OpenVault! Follow these instructions to make a post yourself.

## **1\. Accessing the Repository**

To contribute to **OpenVault**, visit the [Official OpenVaultFiles GitHub Repository](https://github.com/AlpineRobotics25710/OpenVaultFiles). 

## **2\. Forking the Repository**

Instead of cloning the repository, you should fork it. Forking creates a copy of the repository under your GitHub account, allowing you to make changes independently.

**Steps to Fork the Repository:**

1. Go to the [Official OpenVault GitHub Repository](https://github.com/AlpineRobotics25710/OpenVaultFiles).  
2. Click on the **Fork** button at the top-right corner of the page.  
3. Wait for GitHub to create a fork under your account.

**Video Guide:** [How to Fork a Repository](https://www.youtube.com/watch?v=07quEzZ-sJE)

## **3\. Adding Your Files**

Once you've forked the repository, you can add your files directly through GitHub.

### **Required Files:**

**Each contribution** should have a **folder** containing:

1. An **`info.json`** file with metadata.  
2. A **preview image** (`.png` file) named as specified in `info.json`.

### **Creating `info.json`**

1. Navigate to the appropriate folder in your forked repository (e.g., `ftc/cad/drivetrains/`).  
2. Create a folder following this naming structure: “YourTeam\#-NameOfContribution”  
   1. To create a new folder, type the folder name and then “/”  
   2. E.g. 25710-SamplePost/  
3. Then inside the folder:  
   1. Click **Add File \> Create New File**.  
   2. Name the file **`info.json`**.  
   3. Copy and modify the corresponding template for CAD, Code, or Portfolio contributions([Given at the bottom of this document](#templates-for-contributions)).  
5. Click **Commit Changes** to save.

### **Uploading the Preview Image**

1. In the same folder, click **Add File \> Upload File**.  
2. Upload your **PNG preview image** (named exactly as in `info.json`).  
3. Click **Commit Changes**.

**4\. Example File Structure**

Your submission should follow this format:

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
3. Add a title and description explaining your changes/contribution.  
4. Click **Create Pull Request**.

**Video Guide:** [How to Make a Pull Request](https://www.youtube.com/watch?v=nCKdihvneS0)

## **6\. Review & Approval**

Once you submit a pull request, maintainers will review it. If changes are needed, they'll provide feedback. Once approved, your contribution will be merged into **OpenVault**\!   
**Thank you** for contributing to the FTC robotics community\!

# **Templates for Contributions:**

1. CAD contributions should follow this **`info.json`** file format:

```javascript
{
    "preview-image-name": "your-image-file-name.png",
    "title": "The name of your project",
    "author": "Your Name or you team's name",
    "description": "Brief description of your CAD contribution.",
    "used-in-comp": true
    "team-number": "Your Team Number",
    "years-used": "the years you used this (e.g. 2023-2024, N/A if necessary)",
    "onshape-link": "Your CAD link"
}
```

2. Code contributions should follow this **`info.json`** file format:

```javascript
{
	"preview-image-name": "your-image-file-name.png",
      "download-name": "sample-code.png",
	"title": "Sample Drivetrain",
	"author": "Your Name or you team's name",
	"description": "Description of your code contribution",
	"used-in-comp": true,
	"team-number": "25710",
	"years-used": "2024-2025",
	"language": "Java, Python"
}
```

3. Portfolio contributions should follow this **`info.json`** file format:

```javascript
{
	"preview-image-name": "your-image-file-name.png",
"file-name": "sample-drivetrain.png",
	"title": "Sample Drivetrain",
	"author": "Arjun Mahajan",
	"description": "Description of your portfolio submission",
	"team-number": "25710",
	"years-used": "2024-2025",
	"awards-won": "Inspire, Think"
}
```

## 

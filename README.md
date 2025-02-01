# OpenVault - Contribute

## How to Contribute

Follow these steps to add and open-source your own files on OpenVault.

---

## Step 1: Go to the OpenVault Repository

To contribute to OpenVault, visit the [Official OpenVaultFiles GitHub Repository](https://github.com/AlpineRobotics25710/OpenVaultFiles).

---

## Step 2: Fork the Repository

Click the **Fork** button at the top-right of the repository to create your own copy.

**Video Guide:** [How to Fork a GitHub Repository](https://www.youtube.com/watch?v=nCKdihvneS0)

---

## Step 3: Add a Folder (and adding `info.json`) via GitHub

Once you've forked the repository, you can add your files directly through GitHub. **But first**, we have to **create a folder for your files**.

### Creating Your Folder:

1. Navigate to the appropriate folder in your forked repository (e.g., `ftc/cad/arms/`).
2. Create a **folder** following this **naming structure**: `YourTeam#-NameOfContribution`
    - To create a new folder, first click on **Add file** in the right-hand corner and click **Create new file**.
    - In the textbox that appears, type the folder name followed by `/`.
    - Example: `25710-ArmCadV1/`
    - A new textbox should automatically appear.
3. Do not click out of this text box. We will tell you what to put here in the next step.

---

## Step 4: Add Your Files to Your Contribution Folder via GitHub

Once you've created your folder, you can add your files directly through GitHub as well.

### Required Files:

Each contribution folder should have:

1. An `info.json` file with metadata.
2. A preview image (`.png` file) named as specified in `info.json`.

### Adding your `info.json` file:

On the same page that you created your folder, and in the same text box that you created your folder with:

1. Type `info.json` in the textbox that appears.
2. Once you have named your file `info.json`, use one of the **corresponding formats** (based on what type of contribution you are submitting):

#### **CAD Contribution** `info.json` format:

```json
{
    "preview-image-name": "your-preview-image.png",
    "title": "Title of your CAD",
    "author": "Your Name",
    "description": "Describe your CAD, including unique features.",
    "used-in-comp": true,
    "team-number": "Your Team Number",
    "years-used": "Year(s) Used",
    "onshape-link": "Link to your CAD model on Onshape"
}
```

#### **Code Contribution** `info.json` format:

```json
{
    "preview-image-name": "your-image-file-name.png",
    "download-name": "name of your file.zip",
    "title": "title of your code contribution",
    "author": "your name or your team's name",
    "description": "description of your code contribution",
    "used-in-comp": true,
    "team-number": "your team number",
    "years-used": "years you used it",
    "language": "languages-used"
}
```

#### **Portfolio Contribution** `info.json` format:

```json
{
    "preview-image-name": "your-image-file-name.png",
    "file-name": "name of portfolio-file.pdf",
    "title": "name of your portfolio-submission",
    "author": "your name or your team's name",
    "description": "description of your portfolio submission",
    "team-number": "your team number",
    "years-used": "years you used it",
    "awards-won": "awards this portfolio won"
}
```

3. Click **Commit Changes** to save.

### Uploading Your Preview Image:

1. Make sure you are in the same folder that you created.
2. Click **"Add file" → "Upload files"** and upload your image.
3. Click **Commit Changes** to save.

### Uploading Your Download (for code and portfolio contributions only):

1. Make sure you are in the same folder that you created.
2. Click **"Add file" → "Upload files"** and upload your file.
3. If you are uploading a portfolio, ensure it is a `.pdf` file. If you are uploading code, compress it into a `.zip` file and upload that.
4. Click **Commit Changes** to save.

**Important Note:**

- Your preview image and other file names should match the names specified in `info.json`, otherwise, the files will not be found.
- The `used-in-comp` field must be either `true` or `false` (without quotes).

---

## Step 5: Create a Pull Request

Once you've added your files, submit a **Pull Request (PR)** to merge your changes into the main repository.

### Steps to Create a Pull Request:

1. Go to your forked repository.
2. Click **Contribute > Open Pull Request**.
3. Add a title and description explaining your changes/contribution (make sure to include the name of your contribution folder).
4. Click **Create Pull Request**.

**Video Guide:** [How to Make a Pull Request](https://www.youtube.com/watch?v=nCKdihvneS0)

---

## Step 6: Wait for Review

Once you submit a pull request, maintainers will review it.

- If changes are needed, we'll provide feedback.
- Once approved, your contribution will be merged into **OpenVault**!

**Thank you** for contributing to the FTC robotics community!

# StepWise

Welcome to the StepWise project! This is a simple website that outlines a step-by-step process. Each step has a brief description, and you can click on each step to read more details.

## How to Update the Website

The website content is stored in easy-to-edit Markdown files. You can update the steps and descriptions by editing these files directly in this GitHub repository.


### 1. Edit a Step
  1. Navigate to the content/ folder in the repository. You’ll see files named step1.md, step2.md, step3.md, etc.
  2. Click on the file corresponding to the step you want to edit.
  3. Click on the pencil icon (✏️) to edit the file.
  4. Modify the content within the file. For example, you can change the title, description, or detailed content.
  5. After making your changes, scroll down to the bottom of the page.
  6. In the "Commit changes" section, write a brief summary of what you changed (e.g., "Updated Step 1 description").
  7. Click the "Commit changes" button.

### 2. Add a New Step

If you need to add a new step:
  1. Navigate to the content/ folder.
  2. Click "Add file" > "Create new file".
  3. Name your new file something like step5.md.
  4. Add the following structure to your new file:
  ```markdown
  ---
  title: "Step 5: Your Step Title"
  description: "A brief description of this step."
  ---

  ## Step 5: Your Step Title

  Detailed content for Step 5 goes here.
``` 
 5. Fill in the title, description, and detailed content.
 6. Commit the new file as described above.

### 3. Deploying Changes

You don’t need to worry about manually deploying the site. Once you make changes to any Markdown file and commit them, the website will automatically update within a few minutes. This is done using GitHub Actions, which handles the deployment for you.

## Viewing the Website

The live website is available at: https://Lillevang.github.io/StepWise/

You can visit this URL anytime to see the latest version of the site with all your changes.

## Troubleshooting

If you notice something isn’t displaying correctly or have any questions about editing the content, please reach out to the project maintainer.

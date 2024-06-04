# Importing Custom Xcode Template

This guide will walk you through the process of importing your own custom Xcode template.

## Prerequisites
- Xcode installed on your Mac

## Steps to Import Custom Xcode Template

### Step 1: Create Template Directory
1. Open Terminal.
2. Run the following command to create a new directory with a `.xctemplate` extension:

    ```bash
    mkdir MyCustomTemplate.xctemplate
    ```

### Step 2: Add Template Files
1. Place your template files inside the `MyCustomTemplate.xctemplate` directory.

### Step 3: Copy to Xcode Templates Location
1. (Optional) Create ``Template`` folder if you haven't already by run the following command:

    ```bash
    mkdir ~/Library/Developer/Xcode/Templates/
    ```

2. In Terminal, run the following command to copy the `MyCustomTemplate.xctemplate` directory to the Xcode Templates folder:

    ```bash
    cp -R MyCustomTemplate.xctemplate ~/Library/Developer/Xcode/Templates/
    ```

### Step 4: Restart Xcode
1. Close Xcode if it's open.
2. Reopen Xcode.

## Verify Custom Template
- Open Xcode and create a new file.
- Your custom template should now appear in the list of available templates.

Congratulations! You have successfully imported your custom Xcode template.


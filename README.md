# README: Ecos Website Repository

Welcome to the Ecos website repository on GitHub! This README file will guide you through the process of accessing and running the website files, as well as deploying any changes you make to the website.

## Table of Contents
1. [Accessing Website Files](#user-content-1-accessing-website-files)
2. [Running the Website](#user-content-2-running-the-website)
3. [Deploying Changes](#user-content-3-deploying-changes)

### 1. Accessing Website Files

The website files for the Ecos project are located in a folder named "ecos" within this repository. Here are the steps to access these files:

1. **Clone the Repository:** If you haven't already, clone this GitHub repository to your local machine using the following command:

   ```bash
   git clone https://github.com/ipese/ecos.git
   ```
2. **Navigate to the "ecos" Folder:** Once the repository is cloned, navigate to the "ecos" folder using the `cd` command:

   ```bash
   cd ecos/ecos
   ```

Now, you should be in the directory where the website files are located.

### 2. Running the Website

To run the Ecos website locally, you need to have [Quarto](https://quarto.org/) installed. Quarto is a tool for creating and publishing documents, including websites. If you don't have Quarto installed, please follow the [installation instructions](https://quarto.org/docs/getting-started/installation/) provided on their website.

Once Quarto is installed, you can easily preview the website by running the following command from within the "ecos" folder:

```bash
quarto preview
```

This command will build and serve the website locally, making it accessible via a web browser. You can view the website by opening your browser and navigating to the provided URL (usually something like `http://localhost:4000`).

### 3. Deploying Changes

To deploy changes to the Ecos website, you will need to follow these steps:

1. **Make Your Changes:** Make the desired changes to the website files within the "ecos" folder.

2. **Commit Your Changes:** After making your changes, commit them to your local Git repository using the following commands:

   ```bash
   git add .
   git commit -m "Description of the changes"
   ```

3. **Create a Pull Request:** Push your changes to your GitHub fork or branch of the repository and create a pull request (PR) to the `main` branch of the original Ecos repository. This will notify the project's code owners and allow them to review your changes.

4. **Wait for Review:** The code owners will review your pull request and either accept it or provide feedback for revisions. Once your changes are approved, they will be merged into the main branch, and the website will be updated accordingly.

Please be aware that only authorized contributors have the privilege to merge changes into the main branch. If you do not have authorization, kindly request permission from the repository owner. We will review your request and determine whether granting you access is necessary.

That's it! You should now be able to access, run, and deploy changes to the Ecos website repository. If you have any questions or need further assistance, please reach out to the project maintainers or code owners.

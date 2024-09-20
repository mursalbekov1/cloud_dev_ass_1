# Assignment 1: Cloud Application Development - Answers

## Exercise 1: Setting Up Google Cloud SDK

### Questions
1. **What command did you use to authenticate with your Google account?**
   - `gcloud init`

2. **How did you set the default project?**
   - I set the default project by selecting `ass-1-cloud-merey` during the `gcloud init` process.

3. **What information does the `gcloud info` command provide?**
   - `gcloud info` provides details about the current configuration, including the active project, account information, and environment settings.

## Exercise 2: Exploring Cloud Shell

### Questions
1. **What is the default home directory in Cloud Shell?**
   - The default home directory is `/home/USERNAME`.

2. **What tools are pre-installed in Cloud Shell?**
   - Pre-installed tools include `gcloud`, `gsutil`, `kubectl`, and various text editors.

3. **How can you open the built-in code editor in Cloud Shell?**
   - The built-in code editor can be opened by clicking the "Open Editor" button in the Cloud Shell interface or by using the `code` command.

## Exercise 3: Managing Projects with Google Cloud SDK

### Questions
1. **How do you list all projects associated with your account?**
   - Use the command: `gcloud projects list`

2. **What command is used to set a default project?**
   - The command is: `gcloud config set project PROJECT_ID`

3. **How do you describe project metadata?**
   - Use the command: `gcloud projects describe PROJECT_ID`

## Exercise 4: Using Cloud Shell for Basic Operations

### Questions
1. **What command did you use to create the directory structure?**
   - I used the command: `mkdir -p myproject/src myproject/tests myproject/docs`

2. **How did you upload a file to a Cloud Storage bucket?**
   - I used the command: `gsutil cp FILE_NAME gs://BUCKET_NAME/`

3. **How can you list the contents of a Cloud Storage bucket?**
   - Use the command: `gsutil ls gs://BUCKET_NAME/`

## Exercise 5: Automating Tasks with Shell Scripts in Cloud Shell

### Questions
1. **What command did you use to make the script executable?**
   - I used the command: `chmod +x setup.sh`

2. **How did you ensure the script was executed correctly?**
   - I ran the script using: `./setup.sh` and verified that it performed the expected tasks.

3. **What steps did your script automate?**
   - The script automated the creation of a new directory, a simple text file, and the setup of a basic Google Cloud configuration (setting a default project).

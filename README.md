# Cloud Application Development - Assignment 1

## Exercise 1: Setting Up Google Cloud SDK

1. **What command did you use to authenticate with your Google account?**
   - `gcloud auth login`
2. **How did you set the default project?**
   - `gcloud config set project [PROJECT_ID]`
3. **What information does the gcloud info command provide?**
   - The `gcloud info` command provides details about the SDK installation, active configuration, account, project, region, and available components.

---

## Exercise 2: Exploring Cloud Shell

1. **What is the default home directory in Cloud Shell?**
   - The default home directory is `/home/<your-username>`.
2. **What tools are pre-installed in Cloud Shell?**
   - Pre-installed tools include `gcloud`, `gsutil`, `kubectl`, `git`, `nano`, and others.
3. **How can you open the built-in code editor in Cloud Shell?**
   - Use the command `cloudshell edit .` or click the "Open Editor" button in the Cloud Shell interface.

---

## Exercise 3: Managing Projects with Google Cloud SDK

1. **How do you list all projects associated with your account?**
   - `gcloud projects list`
2. **What command is used to set a default project?**
   - `gcloud config set project [PROJECT_ID]`
3. **How do you describe project metadata?**
   - `gcloud projects describe [PROJECT_ID]`

---

## Exercise 4: Using Cloud Shell for Basic Operations

1. **What command did you use to create the directory structure?**
   - `mkdir -p myproject/src myproject/tests myproject/docs`
2. **How did you upload a file to a Cloud Storage bucket?**
   - `gsutil cp [FILE_NAME] gs://[BUCKET_NAME]/`
3. **How can you list the contents of a Cloud Storage bucket?**
   - `gsutil ls gs://[BUCKET_NAME]`

---

## Exercise 5: Automating Tasks with Shell Scripts in Cloud Shell

1. **What command did you use to make the script executable?**
   - `chmod +x setup.sh`
2. **How did you ensure the script was executed correctly?**
   - By running `./setup.sh` and verifying the tasks were performed as expected.
3. **What steps did your script automate?**
   - Creation of a new directory, creation of a text file, and setting up a default project using `gcloud config set project [PROJECT_ID]`.


# Getting Started with an Apache Beam Development Environment

## Install Cloud SDK
* Verify if already installed by typing `gcloud` in bash terminal 
* Follow the appropriate [quickstart](https://cloud.google.com/sdk/docs/quickstarts) for your OS
* Initialize tool
  * `gcloud init`
    * Create your own project when prompted
* Set default application credentials
  * `gcloud auth application-default login`

## Download IDE (Integrated Development Environment)

For Java Developers:
* [Download/Install IntelliJ Community Edition](https://www.jetbrains.com/idea/download)
* [Download/Install Java JDK](https://www.oracle.com/technetwork/java/javase/downloads)


For Python Developers:
* [Download/Install PyCharm Community Edition](https://www.jetbrains.com/pycharm/download)

For Developers with only a browser:
* Clone GitHub repos in cloud shell and use code editor
  * [Shorcut to automatically clone DataflowTemplates](https://console.cloud.google.com/cloudshell/open?git_repo=https%3A%2F%2Fgithub.com%2FGoogleCloudPlatform%2FDataflowTemplates&page=shell)
    * Alternatively run: `git clone https://github.com/GoogleCloudPlatform/DataflowTemplates.git` in cloud shell
  * [Shortcut to automatically clone beam-workshop](https://console.cloud.google.com/cloudshell/open?git_repo=https%3A%2F%2Fgithub.com%2Fdanieldeleo%2Fbeam-workshop)
    * Alternatively run: `git clone https://github.com/danieldeleo/beam-workshop.git` in cloud shell

## Open IDE

On the welcome screen:
* Select **Checkout from Version Control**
* Choose **Git** from the dropdown

Enter git repo URL:
* For Java Developers enter:
  * https://github.com/GoogleCloudPlatform/DataflowTemplates.git
* For Python Developers enter:
  * https://github.com/danieldeleo/beam-workshop.git

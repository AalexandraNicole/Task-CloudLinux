# Task 1

## Instalation Instructions

#### RPM-based Linux system

Follow the steps below to install the package:

1. **Downloas the instalation script**

Clone or download the repository that contains the installation script:

```
git clone <repository_url>
```

Or download the ZIP from your project’s repository and extract it.

2. **Locate the Installation Script**

Enter the directory where the installer is located:

```
cd path/to/directory
```

You should see a file named _install_ inside the project directory.

3. **Run the Installation Script**

Execute the installation script:

```
sh install
```

4. **Install the Required Package and Version**

After the script completes, install the necessary package (and the correct version) that the project depends on.

Use the package manager for RPM-based systems:

```
sudo yum install <package>-<version>
```

### Questions for the team

What is the exact name of the dependency package?

What specific version must users install?

Does the install script require root privileges?

# Task 2

### Uninstalling the Package

You can remove the package with the following command:

```
sudo yum remove mypackage
```

This command removes:

- the installed package
- any associated files not required by other applications

After removal, you can confirm that it is no longer installed:

```
rpm -q mypackage
```

###### Cornea Alexandra-Nicoleta

**Leave Request App**

This project implements a Leave Request Application using SAPUI5 for the frontend and RAP (RESTful ABAP Programming) for the backend on SAP BTP ABAP Environment.

**Project Overview**
- Frontend: SAPUI5 (developed locally with VS Code)
- Backend: RAP OData service in ABAP Cloud
- Source control: GitHub repository with proper documentation and versioning

**Setup and Development Environment**

This section documents the setup steps and tools installed to start the development.

1. Linux-only Platform Setup
Rebooted the system and configured it to run Linux exclusively (Ubuntu/Debian based)

Removed other OS options and set Linux as the default boot environment

(You can add your specific commands or BIOS/UEFI steps here if you want.)

2. Installed VS Code
Downloaded and installed Visual Studio Code IDE from the official website:
https://code.visualstudio.com/

Verified installation by running:

bash
Copy
Edit
code --version

3. Java JDK, Eclipse IDE and ABAP Cloud Setup

Note: Java JDK is needed when installing Eclipse on Linux platform as it acts as foundation for Eclipse

- Installed Java JDK in command line following below steps

        in Terminal:
        sudo apt update
        sudo apt install openjdk-17-jdk -y

- Verified Java installation:

        java -version

- Installed Eclipse IDE from:
        https://www.eclipse.org/downloads/

- Extrated the eclipse file using tar command:

        tar -xvzf <eclipse.tar.gz>

- Once extracted just executed the intstalltion file "./eclipse"

- Installed ABAP Development Tools (ADT) plugin inside Eclipse:

        - Open Eclipse → Help → Install New Software

        - Add update site: https://tools.hana.ondemand.com/latest

        - Select “ABAP Development Tools” and install

        - Connected Eclipse to SAP BTP ABAP Cloud environment:

- Created new ABAP Cloud project

        - Used service key JSON file from BTP subaccount

        - Established connection to cloud ABAP backend

- Next Steps

- Scaffold SAPUI5 frontend application using yo easy-ui5 generator in VS Code

- Develop RAP backend in ABAP Cloud system

- Connect frontend to RAP OData service

- Implement leave request business logic

- Documentation
    For detailed setup instructions, refer to the docs folder:

    - docs/setup/eclipse-setup.md

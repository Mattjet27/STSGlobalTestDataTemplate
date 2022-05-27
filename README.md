# STSGlobalTestDataTemplate
Template files for managing Global Test Data when developing a test program for the NI Semiconductor Test System (NI STS). 

All LabVIEW files were created using LabVIEW 2019.

Please refer to the documentation labeled "STS Global Test Data Management" within the repository for further details.

## Instructions: How to add and use the GlobalTestData template with an existing STS project
1. Download the [latest release](https://github.com/Mattjet27/STSGlobalTestDataTemplate/releases) of the Global Test Data template files (`GlobalTestData.zip`). 
2. Unzip the `GlobalTestData.zip` file into your test program’s `Code Modules/Common` directory.
3. Ensure `Code Modules/Common/GlobalTestData` has been added to your LabVIEW project.
4. Define & add new application specific properties to the GlobalTestData class.
   - Create both a Read & Write VI for each new property. Refer to “Workflow – Creating A New Property slides” within the acompanying GlobalTestData-ReadMe.pdf file.
   - Repeat as needed to scale during test program development

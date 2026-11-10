# 📘 Complete Tosca Cloud Agentic Automation Setup Guide

For a complete end-to-end implementation, refer to the detailed PDF guide:

👉 [Tosca Cloud Agentic Automation – Complete Setup Guide](./Tosca%20Agentic%20Test%20Automation.pdf)


The guide covers the setup from scratch with detailed step-by-step instructions and screenshots.

---
🧠 **Tosca Agentic Test Automation (Tosca collabs with AI to create magic)**

Tricentis has integrated Agentic Test Automation into Tricentis Tosca which enables Quality Engineering Teams or individual to create modules, test cases and manage end-to-end test suites with ease using simple natural language prompts.

---
## 🌟 Key Advantages:
* **Natural Language Test Generation:** Mention instructions in plain English, and the agent automatically translates them into executable modules, test steps, and values without manual intervention.
* **Dual Execution Modes:**
  <br>&nbsp;&nbsp;&nbsp;&nbsp;⮚ **Co-Create Mode (Default):** Works like pair programming, executing one step at a time and waiting for your feedback.
  <br>&nbsp;&nbsp;&nbsp;&nbsp;⮚ **Autonomous Mode:** Runs sequences end-to-end without manual interruption for rapid test generation.
---
## 💥 Big Impact:

➔ Approximately 85% reduction in manual test creation effort.
<br>➔ Up to 60% productivity boost for QA and automation engineers.

---
## 📋 Pre-requisites
1. A **Tosca Cloud Tenant account** equipped with an execution license to create and provision team/cloud agents.
2. A **Tosca On-Premise workspace** with licenses managed securely via Tricentis Tosca Server.

---
> ⚠️ **Version Support Notice:** This configuration guide is only applicable for **Tosca 2025.x** and **versions prior to it**. From **Tosca 2026.1** version onwards the process changes significantly.
---
## 🛠️ Step-by-Step Configuration Guide

This section guides you through the full functional setup required to establish a continuous automation bridge between your local machine, Tosca Commander, and the cloud execution engines.

### Phase 1: Cloud Personal Agent Activation
1. **Navigate to Quick Start Guides:** Log into your Tosca Cloud Tenant homepage, select the **Quick start guides** section, and click on **Download Launcher**.<img width="975" height="452" alt="image" src="https://github.com/user-attachments/assets/95a6c31f-8217-4100-b3a4-2ccc2325ce54" />
2.	**LauncherSetup.exe** downloaded<img width="591" height="245" alt="image" src="https://github.com/user-attachments/assets/49ee0d10-082c-4683-9660-e858dfd60043" />
3.	Right click on the **LauncherSetup.exe** file and select **Run as administrator** to install it<img width="656" height="485" alt="image" src="https://github.com/user-attachments/assets/4654c572-35e7-4e76-b7dc-4a9e43b249df" />
                   
The test scripts on Tosca Cloud are executed through the Launcher<img width="975" height="449" alt="image" src="https://github.com/user-attachments/assets/55ae1b0c-fb3a-4048-b50f-676e5ceb41ee" />
4.	**Activation Code** gets generated on the Tricentis Launcher page. Copy it and use it to activate the launcher<img width="975" height="423" alt="image" src="https://github.com/user-attachments/assets/e0867081-402b-41d6-a189-194e8b742e96" />
5.	The agent is activated. Click on **Retry run** to re-execute the test case.<img width="975" height="455" alt="image" src="https://github.com/user-attachments/assets/d4a1ae4f-87b8-443b-8fc6-2a0dcefdcafa" />
6.	Test Execution in progress through **Tricentis Agent**<img width="975" height="454" alt="image" src="https://github.com/user-attachments/assets/3b4e253d-51af-49e8-b6fb-af92335fff5d" />
### Phase 2: Agentic Test Automation Addon Integration
7.	Download the **ToscaAgenticTestAutomation-1.4.4.msi** file from Tricentis Support portal by raising a service request.
<img width="742" height="85" alt="image" src="https://github.com/user-attachments/assets/a9b7b55f-43d9-42fe-b933-87354fe63abe" />

Download the msi file and then double click to install it.<img width="798" height="454" alt="image" src="https://github.com/user-attachments/assets/92b1f320-bee1-49fc-8f09-75a87b293ed1" />

8.	After installation, login into **On-Prem Tosca Commander workspace**.<img width="975" height="529" alt="image" src="https://github.com/user-attachments/assets/4f9cfc1b-d003-4d10-a2df-479ead40aaa5" />
9.	Click on the **ADDON** tab in the top ribbon<img width="975" height="453" alt="image" src="https://github.com/user-attachments/assets/778fac75-fd34-4648-8c15-0b4432a3e479" />
10.	**Tosca Agentic Test Automation** section is displayed under **ADDON** tab<img width="975" height="399" alt="image" src="https://github.com/user-attachments/assets/d42c0657-41fd-4818-a8c4-71e301bb73df" />
11.	Click on Tosca Agentic Test Automation section<img width="975" height="368" alt="image" src="https://github.com/user-attachments/assets/4b914e79-8f92-4a9e-b1d3-32fce3a8c1ca" />
### Phase 3: Cloud Grid Connection & Authentication
12.	Tosca Agentic Test Automation window appears where we need to enter **Tosca Cloud tenant name**<img width="975" height="479" alt="image" src="https://github.com/user-attachments/assets/fa755bf7-456d-451a-8d65-c2e3e20a94dd" />
The tenant name is the variable part of your Tosca Cloud URL: **https://\<your tenant name\>.my.tricentis.com**
13.	Enter the **Tosca Cloud tenant name** from the Tosca Cloud URL, in the Tosca Agentic Test Automation window and click on Continue<img width="975" height="433" alt="image" src="https://github.com/user-attachments/assets/26770e69-78bb-46ac-beef-60dfabc15f1d" />
<img width="975" height="512" alt="image" src="https://github.com/user-attachments/assets/58cb8090-baaf-4444-8946-d13bffdc2d7f" />
14. Enter your <strong>Tosca Cloud tenant name (User Name)</strong> and <strong>password</strong> with which you log into Tosca Cloud Environment in the Tosca Cloud sign in window displayed.<img width="975" height="405" alt="image" src="https://github.com/user-attachments/assets/6a468b88-5aae-4495-b3bb-6009e0623496" />
<img width="975" height="468" alt="image" src="https://github.com/user-attachments/assets/6c96d84b-704c-471c-8cc4-ac74ea33e2f9" />

### Phase 4: Intent Processing & Workspace Import
15. Tosca Agentic Test Automation is now ready to start. Click on <strong>Start</strong><img width="975" height="460" alt="image" src="https://github.com/user-attachments/assets/42479563-b9fb-480e-8b16-5178bf7050b8" />
16.	In the subsequent Tosca Agentic Test Automation screen we get multiple options to choose from as shown here<img width="975" height="456" alt="image" src="https://github.com/user-attachments/assets/6432e64b-587c-40db-8b06-8cf08417cd22" />
17.	Consider choosing the option – Generate a TestCase<img width="975" height="441" alt="image" src="https://github.com/user-attachments/assets/ba900f0b-e2f7-4647-aaf8-3f4e1e7e71dc" />
18.	Enter your <strong>Tosca Cloud tenant name (User Name)</strong> and <strong>password</strong> again in the Tosca Cloud sign in window displayed.

<mark><strong>Please Note:</strong></mark> Vision AI acts as the visual recognition and perception layer of Tricentis Tosca Agentic Test Automation, allowing AI agents to "see" and interact with user interfaces just like a human user. Agentic Test Automation generates complete test flows and scripts from natural language prompts, while Vision AI translates those intent-driven instructions into actual visual executions across the application screen.<img width="975" height="440" alt="image" src="https://github.com/user-attachments/assets/2aa01f34-bbc3-47bd-8829-8726100a6038" />
19.	Select a <strong>window</strong> to automate<img width="975" height="454" alt="image" src="https://github.com/user-attachments/assets/77ffb37c-70f4-4b56-bf7b-bb8acfd9c468" />
20.	Select <strong>Disable alert</strong> and <strong>No</strong> for the question – <strong>Is this an SAP Fiori application? I have special training to make automation more accurate for SAP Fiori</strong><img width="975" height="457" alt="image" src="https://github.com/user-attachments/assets/c824725e-f2cb-48dc-a7de-1f7f64d24eaa" />
21.	Either provide a simple one liner instruction or an elaborate sequence of instructions (test creation steps) in natural language into the prompt editor window

<strong>Sample Prompt:</strong>
Create an end-to-end web automation test case for demo webshop.
* Open https://tricentis.com in chrome browser
* Select Computers under CATEGORIES
* Wait until Computers categories are displayed
* Verify the different types Computers displayed and select Notebooks
* Capture the Sort by, Display & View as drop-down sections
* Close the particular browser tab<img width="975" height="411" alt="image" src="https://github.com/user-attachments/assets/a02bcd21-a4a2-4ac3-b925-d46ad194964b" />
22.	Tosca Agentic Test Automation reads through the instructions in the prompt taking aid of Vision AI and starts creating the test case. AI Generated Test Case getting created<img width="975" height="453" alt="image" src="https://github.com/user-attachments/assets/0cbe1f5f-c598-4a91-9f77-1621ffb1c05b" />
23.	Once Tosca Agentic Test Automation has finished creating the test case, it will provide a short summary of what it has completed till now, waiting for your next instruction like whether you want to finish building the test case, add additional instructions, modify anything etc.

Click on <strong>Download File</strong> to complete test case creation<img width="975" height="453" alt="image" src="https://github.com/user-attachments/assets/c645fd6c-09fb-427c-8392-9c0af723a7fd" />
24.	Click on <strong>Save and finish</strong> to complete test case saving. The Test Case is saved as a <strong>.tsu</strong> extension file in Downloads section by default<img width="975" height="435" alt="image" src="https://github.com/user-attachments/assets/791e9281-b385-42f7-ab21-324078eea09b" />
25.	Click on <strong>Open file</strong> to view the created test case<img width="975" height="399" alt="image" src="https://github.com/user-attachments/assets/9198d90d-c42f-4bca-af89-b08dd451f0c6" />
<img width="975" height="393" alt="image" src="https://github.com/user-attachments/assets/9c797811-02b0-484e-881d-fe2df3384dca" />
26.	Import the <strong>.tsu</strong> file into Tosca Commander<img width="918" height="111" alt="image" src="https://github.com/user-attachments/assets/1ac43b66-3562-4f80-816b-c926c35cf1e0" />
27.	In Tosca Commander On-Prem first, check out the root project folder and then click on <strong>Import Subset</strong><img width="975" height="420" alt="image" src="https://github.com/user-attachments/assets/75151e1f-73f0-40f8-9ea0-294d95ec8d2f" />
Select the particular <strong>.tsu</strong> file in browse window and click on Open<img width="975" height="453" alt="image" src="https://github.com/user-attachments/assets/f6a1db3b-f1bf-4e48-b285-10b4ad9dc922" />
28.	Select <strong>Import</strong> in Confirm Merge Window<img width="975" height="418" alt="image" src="https://github.com/user-attachments/assets/49e2f56e-5b6d-40c2-8984-e0a6b6321107" />
<mark><strong>Please Note:</strong></mark>Selecting Merge instead of Import will consolidate duplicate modules (Existing modules & new modules generated through Agentic Test Automation of same type) into a single module

29.	The created test case along with the modules created as part of it are imported<img width="975" height="441" alt="image" src="https://github.com/user-attachments/assets/7c43c823-a587-4e61-b847-9eaf8e1a803e" />
30.	The list of <strong>modules</strong> imported<img width="878" height="508" alt="image" src="https://github.com/user-attachments/assets/27d44c15-b050-475a-bacd-982d2dd01199" />
The <strong>test case with test steps</strong> imported<img width="975" height="484" alt="image" src="https://github.com/user-attachments/assets/544bed54-d5e4-46df-9f04-c6358a1d989f" />
<mark><strong>Please Note:</strong></mark>The modules and test cases created through Tosca Agentic Test Automation may not be accurate. Hence, modules may require rescanning & test cases or test steps may require modification etc. to refine and fine tune them as per the exact functional flow.



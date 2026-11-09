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
7.	Download the **ToscaAgenticTestAutomation-1.4.4.msi** file from Tricentis Support portal by raising a service request.<img width="742" height="85" alt="image" src="https://github.com/user-attachments/assets/a9b7b55f-43d9-42fe-b933-87354fe63abe" />

Download the msi file and then double click to install it.<img width="798" height="454" alt="image" src="https://github.com/user-attachments/assets/92b1f320-bee1-49fc-8f09-75a87b293ed1" />

8.	After installation, login into **On-Prem Tosca Commander workspace**.<img width="975" height="529" alt="image" src="https://github.com/user-attachments/assets/4f9cfc1b-d003-4d10-a2df-479ead40aaa5" />
9.	Click on the **ADDON** tab in the top ribbon<img width="975" height="453" alt="image" src="https://github.com/user-attachments/assets/778fac75-fd34-4648-8c15-0b4432a3e479" />
10.	**Tosca Agentic Test Automation** section is displayed under **ADDON** tab<img width="975" height="399" alt="image" src="https://github.com/user-attachments/assets/d42c0657-41fd-4818-a8c4-71e301bb73df" />
11.	Click on Tosca Agentic Test Automation section<img width="975" height="368" alt="image" src="https://github.com/user-attachments/assets/4b914e79-8f92-4a9e-b1d3-32fce3a8c1ca" />
12.	Tosca Agentic Test Automation window appears where we need to enter **Tosca Cloud tenant name**<img width="975" height="479" alt="image" src="https://github.com/user-attachments/assets/fa755bf7-456d-451a-8d65-c2e3e20a94dd" />
The tenant name is the variable part of your Tosca Cloud URL: **https://\<your tenant name\>.my.tricentis.com**
13.	Enter the **Tosca Cloud tenant name** from the Tosca Cloud URL, in the Tosca Agentic Test Automation window and click on Continue<img width="975" height="433" alt="image" src="https://github.com/user-attachments/assets/26770e69-78bb-46ac-beef-60dfabc15f1d" />
<img width="975" height="512" alt="image" src="https://github.com/user-attachments/assets/58cb8090-baaf-4444-8946-d13bffdc2d7f" />
14. Enter your <strong>Tosca Cloud tenant name (User Name)</strong> and <strong>password</strong> with which you log into Tosca Cloud Environment in the Tosca Cloud sign in window displayed.<img width="975" height="405" alt="image" src="https://github.com/user-attachments/assets/6a468b88-5aae-4495-b3bb-6009e0623496" />
<img width="975" height="468" alt="image" src="https://github.com/user-attachments/assets/6c96d84b-704c-471c-8cc4-ac74ea33e2f9" />
15. Tosca Agentic Test Automation is now ready to start. Click on <strong>Start</strong><img width="975" height="460" alt="image" src="https://github.com/user-attachments/assets/42479563-b9fb-480e-8b16-5178bf7050b8" />
16.	In the subsequent Tosca Agentic Test Automation screen we get multiple options to choose from as shown here<img width="975" height="456" alt="image" src="https://github.com/user-attachments/assets/6432e64b-587c-40db-8b06-8cf08417cd22" />


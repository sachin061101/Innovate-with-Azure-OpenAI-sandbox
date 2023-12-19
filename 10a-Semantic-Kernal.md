# 10 a Semantic Kernal

## Introduction

In the prior, you effectively deployed models within the Azure OpenAI service. Now, in this subsequent challenge, your exploration will focus on Semantic Kernel by running Python/dotnet Jupyter notebooks.

The open-source Semantic Kernel streamlines the amalgamation of AI services, including OpenAI, Azure OpenAI, and Hugging Face, into traditional programming languages like C# and Python.

### Task: Setup configuration for Semantic Kernel
1. Open **Visual Studio Code** from the Lab VM desktop by double-clicking on it.
2. In Visual Studio Code from menu bar select **File(1)>open folder(2)**.
3. Within **File Explorer**, navigate to **C:\LabFiles** select **semantic-kernel** click on **Select folder(2).**
4. In **Visual Studio Code**, click on **Yes, I trust the authors** when **Do you trust the authors of the files in this folder?** window prompted.
5. Click on **.env.example** file, replace the values and save the file by pressing **ctrl+s** while renaming it as **.env**.
   | **Variables**                            | **Values**                                                                              |
   | ---------------------------------------- |-----------------------------------------------------------------------------------------|
   | OPENAI_API_KEY                           | Replace the value with the **AZURE OPENAI API KEY** which you noted in Task 2 step 3    |
   | OPENAI_ORG_ID                            | Replace the value with the **AZURE OPENAI ENDPOINT** which you noted in Task 2 step 3   |
   | AZURE_OPENAI_DEPLOYMENT_NAME             | **gpt-35-turbo**                                                                        |
   | AZURE_OPENAI_ENDPOINT                    |                                                         |
   | AZURE_OPENAI_API_KEY                     | |
   | AZURE_AI_SEARCH_API_KEY     | |
   | AZURE_AI_SEARCH_URL        |                                              |

### Task: Setup orchestration for Semantic Kernel
1. In the Visual Studio Code navigate to **semantic-kernel\python\notebooks** folder and select **03-semantic-function-inline.ipynb**.
   > **Note**: In the previous task, we have already updated the values for **AZURE_COGNITIVE_SEARCH_SERVICE_NAME, AZURE_COGNITIVE_SEARCH_ENDPOINT_NAME, AZURE_COGNITIVE_SEARCH_INDEX_NAME, AZURE_COGNITIVE_SEARCH_API_KEY**.
2. From the right corner click on **select Kernal** and on the Choose a Kernel source pop-up, select **available Python 3.10.0** env. This will set the Python Environment.
3. **Execute the notebook cell by cell** (using either Ctrl + Enter to stay on the same cell or Shift + Enter to advance to the next cell) and observe the **results of each cell** execution.
   > **Note:** Make sure **Python Environment** is in a ready State, If not please wait for 15 to 20 seconds.

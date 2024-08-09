Code Execution Steps

Dataset url - https://www.kaggle.com/datasets/sadmansakibmahi/plant-disease-expert/data

Follow up from our last discussion - https://dev.azure.com.mcas.ms/Dbeckley6774/INFO8665%20-%20Projects%20in%20Machine%20Learning%20(Plantify)/_workitems/edit/105

Not sure if you can access the azure link, here is a screenshot - 
https://asset.cloudinary.com/dk0k3povu/0871e322515f5057f30627593386a560


# **Main Steps**
1. **Install Python**: Ensure that Python is installed on your system. You can download the latest version of Python from the official Python website.

2. **Install Git**: Ensure you have git installed as well. You can download the latest version from the official website.

3. **Clone the project**: Clone the project repository from a version control system like Git. Use the following command in your terminal (git bash shell or any git enabled shell):
    ```
    git clone https://github.com/coachlivinglegend/the-plant-guard.git
    ```

    If you are not cloning the project from github and just unzipping it, then you can skip the above step.

4. **Navigate to the project directory**: Use the `cd` command to navigate to the project directory:
    ```
    cd the-plant-guard
    ```

As an alternative to the above steps you can also use the Github Desktop option or you can also download a zipped version of the repository.

5. **Create a virtual environment**: It is recommended to create a virtual environment to isolate project dependencies. Run the following command to create a virtual environment:
    ```
    python -m venv plant-guard-env
    ```

6. **Activate the virtual environment**: Activate the virtual environment using the appropriate command for your operating system:
    - For Windows (in a powershell or cmd or zsh shell) :
      ```
      .\plant-guard-env\Scripts\activate
      ```
    - For macOS/Linux:
      ```
      source plant-guard-env/bin/activate
      ```

7. **Install project dependencies**: Install the required dependencies by running the following command:
    ```
    pip install -r requirements.txt
    ```

8. **Run the project**: You can run any of the notebook files in the project to see it in action.
    You will be prompted to select a kernel. In the python environments, you can select
    ```
    plant-guard-env
    ```
    If you don't find this environment, just close your code editor and reopen it.

9. You can run any of notebook files
    - EDA
    ```
    plant_id_eda.ipynb
    ```
    and 
     ```
    plant_disease_id_eda.ipynb
    ```

    - Model Training
    ```
    plant-identification.ipynb
    ```
    and 
     ```
    plant-disease-identification.ipynb
    ```

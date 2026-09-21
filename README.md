1. Project Structure:
Shows the overall organization of the Olympic Data Engineering project, including Azure Data Factory pipelines, Databricks notebooks, data files, and project configuration.
<img width="1536" height="1024" alt="project_structure_p2" src="https://github.com/user-attachments/assets/2bbc6871-f1c1-4422-9e7d-e52c881f3d43" />

2. Resource Group:
Azure Resource Group - 
Shows the Azure Resource Group containing the cloud resources used in the project, including Azure Data Factory, Azure Data Lake Storage Gen2, and Azure Databricks.
<img width="949" height="477" alt="ResourceGroup_p2" src="https://github.com/user-attachments/assets/3e557ea0-2e0f-4fe4-b149-031f35c7aa77" />

3. Azure Data Factory:
Shows the data ingestion pipelines built in ADF. The project uses both individual Copy Activities for file-wise ingestion and a parameterized Copy Activity with a single reusable linked service to process multiple files efficiently.
<img width="959" height="471" alt="ADF_p2" src="https://github.com/user-attachments/assets/911ab701-8948-4ebe-9d44-6e1011a15f63" />

4. Azure Databricks:
Shows the Databricks environment used to process and transform the Olympic datasets using PySpark, with the transformed and curated data stored in the Gold layer of ADLS Gen2.
<img width="952" height="471" alt="Databricks_p2" src="https://github.com/user-attachments/assets/c97ea503-c74e-4be3-9593-f53b19918123" />

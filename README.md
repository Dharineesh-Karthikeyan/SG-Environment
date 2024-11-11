# SG ♥ Environment Dashboard

Singapore is recognized as one of the healthiest countries globally, renowned for its stringent environmental protection policies and proactive approach to sustainability to ensure high standards of air, land, and water quality. This project utilizes AWS technologies—including Amazon S3, Amazon Athena, and Tableau to create a data-driven dashboard that visualizes Singapore's environmental health metrics. By transforming and analyzing government-provided data, the project aims to highlight Singapore's achievements and offer a model for other countries looking to implement sustainable environmental practices.

______________________

### <b>Tools & Technologies:<b>
- Amazon S3: Storage for the raw environmental health datasets.
- Amazon Athena: SQL-based query and transformation engine connected to the S3 data.
- Tableau: Data visualization platform for creating an interactive dashboard.
- Python : Scripting and Connector for AWS.

______________________

## Project Pipeline and Workflow:

<img width="1200" alt="image" src="https://github.com/user-attachments/assets/f9d92ea3-3043-486d-b6bf-4d9fef3d4598">


Simplified Flow:
1. Source Datasets: Data is scattered between various government sources and datasets.
2. Data Lake (Conceptual layer) : Data from various sources is ingested and structured.
3. Python Script: Uses Boto3 to push data from the source into Amazon S3 and also loads it into Amazon Athena for processing.
4. Amazon S3: Raw data (data lake) is stored and organized in S3, serving as a staging area.
5. Amazon Athena: Data is transformed and queried using SQL.
6. Tableau: Transformed data is visualized in an interactive dashboard for analysis.

Additionally, for security purposes - IAM Roles are used to manage secure access for both Python script (to S3 and Athena) and Tableau (to Athena), ensuring proper data access at each stage.

___________________

## Dashboard Design:
<img width="720" alt="image" src="https://github.com/user-attachments/assets/f3d44195-7682-4bcb-8cc5-02b5e09c520b">


____________________

## Project Report and Presentation:

A detailed professional report and presentation is also included that bridges the gap between numerical values shown in the dashboards and real-world information. I have helped identify and outline the specific methods, techniques, and laws that Singapore has implemented to maintain its high environmental standards. By connecting these laws, such as strict air and water quality regulations, land management policies, and sustainable urban planning practices, I have provided a deeper understanding of how these measures directly impact environmental health, beyond just numerical data.

The analysis helps highlight how Singapore is one of the healthiest countries globally and teaches other countries how they can adopt similar strategies to improve their own environmental outcomes. I have also suggested actionable ideas for Singapore to further enhance its environmental sustainability in the future.

Overall, the report helps policy makers and environment entusiasts see the bigger picture and understand the driving forces behind the data, while the presentation condenses these insights into an accessible fun filled format to learn from Singapore's example and consider ways to implement these strategies in their own countries.

Click Here to view the [Report or the [Presentation

_____________________

## License
This project is licensed under the MIT License.

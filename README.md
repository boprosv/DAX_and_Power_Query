# Power BI Code Assistant Pro
Dax and Power Query Assistant


This Power BI Code Assistant Pro is a sophisticated Streamlit application designed to accelerate Power BI development by providing AI-powered code generation for both DAX (Data Analysis Expressions) and Power Query (M) languages. This tool integrates with OpenAI's GPT-4o model to deliver accurate, schema-aware code suggestions while incorporating advanced features like XMLA endpoint validation, template management, and schema-aware context.

![alt image](https://github.com/boprosv/DAX_and_Power_Query/blob/main/Screenshot%202025-03-27%20095316.png?raw=true)

Key Features:

1.AI-Powered Code Generation:

-Generates DAX measures and Power Query (M) transformations from natural language prompts.

-Supports schema-aware suggestions when table structures are provided.

-Optimized for readability with proper formatting and comments.

2.XMLA-Based DAX Validation

-Validates generated DAX against a Power BI XMLA endpoint (requires Power BI Premium or Premium Per User).

-Provides instant feedback on syntax and semantic correctness.

3.Template Management System

-Prebuilt templates for common patterns (e.g., time intelligence in DAX, date table creation in Power Query).

-Users can save, browse, and delete custom templates.

4.Schema Awareness

-Upload CSV/Excel files to define table schemas for context-aware code generation.

-Displays sample data and column structures for reference.

5.Conversational Memory

-Maintains context from previous interactions for more coherent follow-up requests.

-Full history of generated code with reusability options.

6.Enterprise-Grade Security

-Supports NTLM authentication for XMLA validation.

-Credentials stored securely in a YAML file (not hardcoded).


![image](https://github.com/user-attachments/assets/de5393cb-fd21-4a49-b5c6-f5c6ad70da2c)


Demo Scenario

User Request:

"Create a DAX measure for rolling 30-day sales by product category."

![image](https://github.com/boprosv/DAX_and_Power_Query/blob/main/Screenshot%202025-03-27%20101353.png?raw=true)

App Response:

-Generates a properly formatted DAX measure using CALCULATE() and DATESINPERIOD().

-Optionally validates the DAX against the XMLA endpoint.

-Saves the code to history for future reuse.

![image](https://github.com/boprosv/DAX_and_Power_Query/blob/main/Screenshot%202025-03-27%20101513.png?raw=true)

This Power BI Code Assistant Pro bridges the gap between natural language prompts and production-ready Power BI code, reducing development time while improving accuracy. Its unique combination of AI generation + real validation + schema awareness makes it a powerful tool for both beginners and advanced Power BI developers.

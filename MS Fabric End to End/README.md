# datasticot
Github repository to store all code samples from the datasticot blob: https://datasticot.com/

For this code to work, you need a Microsoft Fabric Lakehouse in a workpace attached to a Microsoft Fabric capacity. You also need to set up an API key to use Riot Games API. My API Key is stored in an Azure Key Vault secret so that it never directly appears in the notebooks code.

These notebooks use pySpark to ingest data from the Riot Games API into a Lakehouse that serves as the bronze layer of a medallion architecture.
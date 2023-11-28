# How to setup Google Cloud Credentials

In order to use the Vertex AI SDK for Python for LLMs, complete the following steps:
1. Create Service Credentials
   1. Create a Key for the Service Account
   2. Downloading Key as JSON File
   3. Set Google Application Credentials Environment Variable
2. Install Requirements from via "pip install requirements.txt"
3. Connecting Vertex API Python API Calls

## How to Create Service Credentials
1. Create Service Credentials 
   1. **Navigate to the Google Cloud Console**: Access the Google Cloud Console and search for 'API & Services'. 
   2. **Access Credentials**: In the left menu, select 'Credentials'. 
   3. **Create Service Account**: Click on 'Create Credentials' and choose 'Service Account'. 
   4. **Configure Service Account**:
   - Enter a name for the Service Account. 
   - Optionally, provide a description. 
   - Click 'Create and Continue'.


2. Configure Service Account Permissions (Optional)
   1. **Assign Roles**: If needed, assign roles to the service account. For using Vertex AI, consider selecting the 'Vertex AI Service Agent' role. 
   2. **Add Users**: Optionally, grant other users access to this service account. 
   3. **Complete Setup**: Click 'Done'.
   

3. Generate Service Account Key 
   1. **Find the Service Account**: Locate your new service account in the 'Service Accounts' section. 
   2. **Add Key**: Select the service account, navigate to 'Keys', and choose to add a new key. 
   3. **Download Key**: Select 'JSON' as the key type and click 'Create'. The key will download automatically—usually to your system's default download folder.


4. Set Up Environment for API Access
   1. **Move Key to Working Directory**: (Optional) Move the downloaded JSON key to your project's working directory for easier reference.
   2. **Set Environment Variable**: Configure the Google Application Credentials environment variable. On most systems, this can be set by running:
  

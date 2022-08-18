# Postman

Use postman to test the functionality of the APIs you are interested in.

### Importing

Precondition: the project is cloned to your local computer. Postman app is running.
1. In Postman application click Import on the Environments tab.
   ![Environment importing](docs/images/EnvImport.jpg?raw=true)
2. Drag-and-drop .json files from ./environment to the Import window. Click the Import button.
   ![Drag-and-Drop environment](docs/images/DragAndDropEnv.jpg?raw=true)
   ![Access environment import](docs/images/AcceptEnvImport.jpg?raw=true)
3. Select the required environment. Click Checkmark near environment's name.
   ![Select required environment](docs/images/SelectEnv.jpg?raw=true)
4. Enter your credentials to username, password fields in CURRENT VALUE column.
   ![Enter credentials](docs/images/EnteringСredentials.jpg?raw=true)
5. Click Import on the Collection tab.
   ![Collection importing](docs/images/CollectionImport.jpg?raw=true)
6. Drag-and-drop .json files from ./collection to the Import window. Click the Import button.
   ![Drag-and-Drop collection](docs/images/DragAndDropCollection.jpg?raw=true)
   ![Access collection import](docs/images/AcceptCollectionImport.jpg?raw=true)
7. Send Acquire Token request to generate new token.
   ![Acquire token](docs/images/AcquireToken.jpg?raw=true)

Now you can send any requests from the collection and check its results.

### Swagger Docs

Development environment:   
- [Platform Swagger Dev](https://platform-swagger.dev.everyasset.net)  
- [Organization Swagger Dev](https://organization-swagger.dev.everyasset.net)  

Production environment:  
- [Platform Swagger](https://platform-swagger.everyasset.net)  
- [Organization Swagger](https://organization-swagger.everyasset.net) 
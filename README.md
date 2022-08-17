# Postman

Use postman to test the functionality of the APIs you are interested in.

### Importing

Precondition: the project is cloned to your local computer. Postman app is running.
1. In Postman application click Import on the Environments tab.
   ![Environment importing](docs/images/1.jpg?raw=true)
2. Drag-and-drop .json files from ./environment to the Import window. Click the Import button.
   ![Environment importing](docs/images/2.jpg?raw=true)
   ![Environment importing](docs/images/3.jpg?raw=true)
3. Select the required environment. Click Checkmark near environment's name.
   ![Environment importing](docs/images/4.jpg?raw=true)
4. Enter your credentials to username, password fields in CURRENT VALUE column.
   ![Environment importing](docs/images/5.jpg?raw=true)
5. Click Import on the Collection tab.
   ![Environment importing](docs/images/6.jpg?raw=true)
6. Drag-and-drop .json files from ./collection to the Import window. Click the Import button.
   ![Environment importing](docs/images/7.jpg?raw=true)
   ![Environment importing](docs/images/8.jpg?raw=true)
7. Send Acquire Token request to generate new token.
   ![Environment importing](docs/images/9.jpg?raw=true)

Now you can send any requests from the collection and check its results.

### Swagger Docs

Development environment: [here](https://platform-swagger.dev.everyasset.net)
Production environment: [here](https://organization-swagger.dev.everyasset.net)
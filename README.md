## Steps
1. npm install -g loopback-cli
2. enter 'lb' into command line
3. create endpoints
4. create model
  - lb model
5. name model
6. select 'db (memory)'
7. select PersistedModel
8. Yes, expose API
9. Enter plural form of model (ex: contacts)
10. Select common
11. Create properties for model
12. Press Enter on 'Property name:' line when done creating models
  - create another model if you want to
13. 'node .' starts the loopback server
14. follow the http address provided in the terminal

## Access Control List
1. enter 'lb acl' in terminal
2. Select 'all exisiting models'
3. Select 'All methods and properties'
4. Select 'All (match all types)'
5. Select any authenticated user
6. Select 'Explicitly grant access'

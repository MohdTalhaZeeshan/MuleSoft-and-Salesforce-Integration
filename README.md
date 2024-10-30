In this MuleSoft and Salesforce Integration project, I created a database on freemysqlhosting.net with a contacts table to store essential employee information (name, email, and company). To facilitate communication between this database and Salesforce, I developed an API specification using RAML in Anypoint Platform, with two key resources:

/contacts Resource: Designed to retrieve all employee contact details from the MySQL database hosted online. This allows seamless access to real-time employee information from an external database, making it easy to keep Salesforce and other applications updated.

/submit Resource: Configured to automatically trigger upon any new record insertion in the contacts table. When activated, this resource fetches the new employee’s details and integrates them into Salesforce, ensuring Salesforce’s contact data stays current without manual input.

This integration setup demonstrates real-time data sync between a MySQL database and Salesforce, providing both automation and scalability for managing employee contact data.

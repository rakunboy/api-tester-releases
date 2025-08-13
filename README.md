# API Client App

This application allows you to interact with APIs in a visual and organized way, using JSON files as the base to store and structure information about requests, configurations, and endpoint collections.

## Main Features

- **Management via JSON files:**  
  Each JSON file can contain:
  - Endpoint collections.
  - Configured HTTP requests.
  - Variables and private variables for sensitive data, preventing exposure of information like tokens or passwords.

- **Variable support:**  
  - Public variables: visible and shared in the JSON file.  
  - Private variables: protected and not stored in the file, keeping sensitive information secure.

- **Automatic file generation:**  
  Simply select a directory, and the application will automatically generate the JSON files for each collection and request, simplifying organization and avoiding manual file creation.

- **Git versioning:**  
  JSON files can be versioned using Git, allowing you to:
  - Maintain a clear history of changes.
  - Facilitate collaboration among team members.
  - Manage branches and revisions efficiently.
  - Avoid editing conflicts through change reviews before merging.

- **Team collaboration:**  
  Thanks to versioned and structured files, multiple developers can work simultaneously on the same endpoint collections without losing information or creating inconsistencies.

- **Organization and traceability:**  
  Each JSON file represents a collection of endpoints, variables, and requests, providing an organized and easily reproducible working environment.

## How it works

1. Select a directory where JSON files will be automatically generated.
2. Edit, add, or remove collections, requests, and variables visually.
3. Save the changes in the JSON files.
4. Version the files using Git to maintain a history and facilitate collaboration.

## Usage Recommendations

- Keep each collection in a separate JSON file to improve organization.
- Commit frequently when working in a team to avoid conflicts.
- Use Git branches to test changes or new collections without affecting the main version.
- Use private variables for any sensitive data that should not be exposed in JSON files.

## Benefits

- Facilitates collaborative work on API projects.
- Protects sensitive data through private variables.
- Enables quick reproduction of testing and development environments.
- Ensures all configurations and collections are under version control when configured.
- Provides a complete change history, useful for audits and tracking evolution.

---

This JSON- and Git-based workflow makes API management more organized, collaborative, and secure—ideal for modern development teams.

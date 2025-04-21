The fetch_pr_changes() function retrieves and returns changes from a given GitHub pull request. It takes three parameters, namely repo_owner, repo_name, and pr_number, and it returns a structured list of file changes along with PR metadata.

The code uses the requests library to send authenticated HTTP GET requests, fetching both general PR metadata and detailed file-level changes:

The first API request retrieves high-level PR information, including its title, description, author details, timestamps, and current state.
The second API request fetches details about each file changed in the PR, such as filename, modification status, the number of lines added or removed, and URLs for accessing file contents.
Once the data is retrieved, the function structures and combines the PR metadata with file changes into a dictionary. The file changes are stored in a list, with each entry containing detailed information about a file. The final data structure includes the PR title, description, author, timestamps, state, total count of files changed, and a detailed breakdown of file modifications.


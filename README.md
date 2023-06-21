# migrate-github-to-bitbucket
Migrating the GitHub repository to Bitbucket, including the branches, tags, and open PRs.

* Dependency to Install
    * python3
    * python3-pip
    * gitpython

* Setup API,repository,token,owner : We have to obtain API access tokens for both GitHub and Bitbucket as well as API endpoints,repository.
  
* Clone Code: Clone the GitHub repository locally using Git.
  
* Retrieve Repository Information: Now we have to use the GitHub API to fetch information about the repository that we have to migrate. This includes details such as branches, tags, and open pull requests.

* Create a New Repository on Bitbucket: Now we have to use the Bitbucket API to create a new repository with the same name as GitHub.

* Migrate Branches: Iterate over the branches obtained from GitHub by using the Bitbucket API to create the corresponding branches on the newly created Bitbucket repository.

* Migrate Tags: Iterate over the tags obtained from GitHub by using the Bitbucket API to create the corresponding tags on the Bitbucket repository.

* Migrate Pull Requests: Iterate over the open pull requests obtained from GitHub and create new pull requests on Bitbucket using the Bitbucket API.

* Migrate Code: push the code to the newly created Bitbucket repository.It will help to transfer the data accurately.
  
* Perform Verification: After verify that the migration was successful by comparing the code, branches, tags, and pull requests between the GitHub and Bitbucket repositories.
  

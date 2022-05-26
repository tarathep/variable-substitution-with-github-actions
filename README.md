# Use variable substitution with GitHub Actions

How to use variable substitution action to replace values in XML, JSON and YAML based configuration and parameter files.

Variable substitution lets you insert values, including GitHub secrets, into files in your repository during the workflow run. For example, you could insert an API login and password into a JSON file during the workflow run.

Variable substitution only works for keys predefined in the object hierarchy. You cannot create new keys with variable substitution. In addition, only variables defined as environment variables in the workflow or system variables that are already available can be used for substitution.

ref : https://docs.microsoft.com/en-us/azure/developer/github/github-variable-substitution
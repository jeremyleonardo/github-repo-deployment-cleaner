# Github Repo Deployment Cleaner

A script to clear environment (deployment) data on a Github repo.

Note: it'll remove ALL of your deployments on a repository.


So you want to clean up this Deployment section because you've removed the integration (heroku, or any others) but it's still listed on the github like this:

![image](https://user-images.githubusercontent.com/58095255/187248706-7ff3cf78-6b52-49b0-b560-d0eedff9a3c9.png)

We can easily clean it up with this script.


Usage:
```
npm install
```

```
node . YOUR-PERSONAL-ACCESS-TOKEN your-name/repo-name
```
The Personal Access Token MUST BE `repo_deployment` authorized

The output:
```
30 deployments found
30 deployments marked as "inactive"
30 deployments deleted
Removed Deployments: 30
```


Full credits to <a href="https://stackoverflow.com/users/6569950/spersico">spersico</a> for his answer on <a href="https://stackoverflow.com/questions/53452910/how-to-remove-a-github-environment">Stack Overflow</a>.

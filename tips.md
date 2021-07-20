## To deploy to this app to IBM Cloud Cloud Foundry

```sh
ibmcloud login --sso
ibmcloud target --cf-api http://api.ng.bluemix.net -o walicki@us.ibm.com -s dev
ibmcloud cf v3-push walicki-playbulb
```

`git push` to GitHub isn't really necessary.

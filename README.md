# bst test
Execute the bst test command in our self-host environment runners


# How to use it

Add and step that reference this action bespoken-dashboard-repositories/bst-test@version as a step

```
  e2e-test:
    runs-on: self-hosted
    name: e2e test
    steps:
      - id: bst-test
        uses: bespoken-dashboard-repositories/bst-test@v1
        with:
          SOURCE_ID: 
          JOB_CREATION_TIMESTAMP: 
          VIRTUAL_DEVICE_TOKEN: 
```
Replace the version with the one you are going to use, and set the parameters SOURCE_ID, JOB_CREATION, and JOB_CREATION

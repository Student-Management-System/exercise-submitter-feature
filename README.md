## How to build

0. Clear the `deploy` folder inside this project (or create it as an empty directory)
1. Open `feature.xml` in eclipse.
2. Select the "Overview" tab.
3. On the top right, click "Export a deployable feature".
4. Make sure that this feature is selected (checkbox)
5. Select the `deploy` folder inside this project as the destination.

## How to deploy

Copy the whole content of the `deploy` folder onto a web-server. This should include:

* The files `artifacts.jar` and `content.jar`
* The folders `features` and `plugins` (including their content)

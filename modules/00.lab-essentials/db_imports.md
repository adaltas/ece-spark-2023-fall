# Import notebooks and data to Databricks Workspace

During the lab you will need to import the prepared notebooks and maybe also some detasets. Here you will learn how.

## Import a notebook

When you are in your workspace, click on `Workspace` in the sidebar on the left, then on `v` in the pop-up menu and then on `Import`. All steps are shown below.

![Import notebook](./image/db_import_notebook_1.png)

You can import a notebook as a file or with copy-pasting a link (this doesn't always work).

![Import notebook](./image/db_import_notebook_2.png)

## Execute the code

You have opened notebook, but no clusters running. If you want to execute the code, you need to start a cluster and attach the notebook to it. You can see if the notebook is attached or not just below the title of the notebook.

![Detached notebook](./image/db_opened_notebook.png)

The easiest way to start the cluster and attach the notebook is the following. Go to the first cell with the code and execute it pressing `Shift+Enter` or clicking on the `play icon` in the upper right corner of the cell. You should see the following message.

![Detached notebook](./image/db_detached_notebook.png)

Click `Launch and Run`. After a while, the `Detached` state will be replaced by a green dot and a cluster name, which indicates that the notebook is attached. Also, the execution details will show up at the bottom of the executed cell.

![Attached notebook](./image/db_attached_notebook.png)

## Import a dataset

To import a dataset, you need an active cluster. The easiest way is to open a notebook and run a cell, as described above.

Click on `Data` in the sidebar on the left and then the icon `Create Table` in the upper right corner.

![Import data 1](./image/db_import_data_1.png)

Select your data source and follow the instructions. If you are uploading file from your drive, click `Upload File` and then click the gray surface, to activate the upload interface.

![Import data 2](./image/db_import_data_2.png)

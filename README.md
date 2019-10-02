# formstate
A tool to compare terraform state file and determine the resource differences.

When you have your production running in the cloud, you would be very careful when you trying to update, add or delete a resources. 

This tools help you see the changes between different environment. (Unless you have only 1 environment) 

Of course you can run terraform plan, which give you exactly what will be destroyed and what will be created. 


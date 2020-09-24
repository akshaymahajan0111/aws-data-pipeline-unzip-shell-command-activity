# aws-data-pipeline-unzip-shell-command-activity
Unzip S3 zip file and store extracted data back to S3 using AWS data pipeline service.

## Issues may occure
1. ERROR: Unable to validate instance profile 'DataPipelineDefaultResourceRole' because no role exists with that name.  
Solution: This is strange in my case i just created a new role which is replica of 'DataPipelineDefaultResourceRole' role and attached it to pipeline and it worked

2. Resource is stalled. Associated tasks not able to make progress.   
Solution: In my case it was access issue. Please make sure if you have given correct and enough permissions.

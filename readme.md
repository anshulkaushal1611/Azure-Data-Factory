Steps to run the pipeline:
1. Open Azure data factory. Open getintofilestosnow pipeline. Click Debug button.
2. Pipeline will start executing. In some time, it will be completed successfully.
  
 Ways to validate the results: 
 a. Before executing the pipeline truncate the table mview_weekly_sales by running "Truncate Table mview_weekly_sales".
 b. After running the pipeline successfully, mview_weekly_sales table will be having the desired data.

## Data Version Control

1. Create git repo and clone it in local.
2.  Pip install dvc
3.  dvc init
4.  makdir S3
5.  dvc remote add -d myremote s3
6.  Next "dvc add data/" 
   Now it will ask to do: ("git rm -r --cached 'data'" and "git commit -m "stop tracking data"")
   Because initially we were tracking data/ folder from git so now we remove it for DVC to handle.
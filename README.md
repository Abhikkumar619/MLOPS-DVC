## Data Version Control

1. Create git repo and clone it in local.
```bash
2.  Pip install dvc
3.  dvc init
4.  makdir S3
5.  dvc remote add -d myremote s3

6.  Next "dvc add data/" 
# it will ask to do: ("git rm -r --cached 'data'" and "git commit -m "stop tracking data"")
# Because initially we were tracking data/ folder from git so now we remove it for DVC to handle.


# To track the first verion of data. 
7. dvc commit and dvc push
# Also run the git add . and git commit , git push. 
#  Add the some data to version 1. 

8. dvc status - retrun modified

9. dvc commit and push (for second version.)

10. git add . and commit, push

11. git log -- oneline (for git log shi id)

12 if we want first version get shi add than 

13. git checkout shi_id

14. dvc pull - for first version.


```

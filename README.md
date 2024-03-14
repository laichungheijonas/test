# test
Test.

## How-To

Useful commands:

To load in python:

```
module load python3/3.11.7
```

To create a virtual environment:

```
python3 -m venv [name_of_env]
```

Loading a virtual environment:

```
source /scratch/vj74/cl2788/environments/graphcast_env/bin/activate
```

Install requirements.

```
python -m pip install -r requirment.txt --no-cache-dir
```

Useful commands

```
qstat: gives you queue information
qdel: allows you to delete a job
qsub: allows you to submit a job
quota: how much memory you have used
lquota: how much memory each of your projects are using
nci_account -P vj74 -v ... how much storage
```

## Git Commands

```
git status... gets status of changes.
```

How to commit

```
git add [files I wanted to add]
git commit -m "[summary]"
git push
```

Then do whatever it tells you...

How to pull

```
git pull
```

### Location of Graphcast

Graphcast is located at:

```
/scratch/vj74/cl2788/programs/graphcast
```
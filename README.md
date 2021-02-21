# Place for all datascience learning task






### conda cheetsheet
```
conda env list
conda activate/deactivate <env-name>
# installation of the jupyter notebook package
conda install jupyter
# creating an env.
conda create -n <env-name>
```

### jupyter nb hacks
```
#for commenting a cell
ctrl+ / 

# if cell got deleted by mistake, getting it restored
esp + z 
 
# merging the cell
sft + m
# deleting the selected cells
dd 
# getting help related document in the notebook
help(numpy)

# magic command: 
%run hello.py
## loading the python script
%load example.py 
## returns the cpu time for running a cell
%time
## interactive debugger 
%debug 
## Will list all of the magic command
%lsmagic 
%%script false -> preventing/skipping execution of particular cells (model traning step)
%%latex -> for showing the latex in the jpnb, syntax converting 
```









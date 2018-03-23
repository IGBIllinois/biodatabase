# biodatabase
* Scripts to create databases on the biodatabase machine.
* This database is accessiable to the compute nodes on the biocluster (http://biocluster.igb.illinois.edu)
* https://biodatabase.igb.illinois.edu/phpmyadmin_experiments/

## Commands
* mkdb - Creates the database
```
Usage: mkdb SUFFIX
Database name will be netid_SUFFIX
SUFFIX can contain only lowercase letters and numbers
SUFFIX can only be up to 7 characters long
```

* lsdb - Lists databases
```
Usage: lsdb 
Lists the databases you have access to
```

* rmdb - Removes databases
```
Usage: rmdb DATABASE 
This will delete the database and corresponding user
DATABASE is the full name of the database, netid_SUFFIX
```


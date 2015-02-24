# Installing Vertica using Vagrant

1. Install Virtualbox and Vagrant.

2. Clone or download this repo.

3. Download `vertica_7.1.1-0_amd64.deb` (community edition) from
   http://my.vertica.com, and put the file to the repo directory.

4. Download `vertica-hdfs-connectors-7.1.1-0_amd64.deb` (community edition) from
   http://my.vertica.com, and put the file to the repo directory.

5. cd to the repo directory, do `vagrant up`.

6. You'll see an instruction of how to create a database after installation is complete

The default connection credentials:
* Username: dbadmin
* Password: pass

##fork note

added hdfs support
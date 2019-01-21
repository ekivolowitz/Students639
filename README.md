# UW Madison Software Security Course Project
This project was developed for Professor Barton Miller's Software Security Course as an application to apply [FPVA](http://research.cs.wisc.edu/mist/papers/ccsw12sp-kupsch.pdf) to. 

## Running
For simplicity, I used an absolute path for locating the database. One day I will change that to be a relative path. In order for it to work, go to the `jetty/webapps/root/WEB-INF/src/security/helper/SqlQuery.java` file and change the location variable.
```bash
$ cd jetty
$ java -jar start.jar
```
Now open your web browser and navigate to `localhost:8080`.

### Test users
```
username: some_guy
password: his_password
```

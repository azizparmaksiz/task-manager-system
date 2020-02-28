# Task Manager System
Task Manager System includes:
- [Task Manager Spring Backend Project](https://github.com/azizparmaksiz/task-manager-system/tree/master/task-manager) 
- [Task Manager Angular Frontend Project](https://github.com/azizparmaksiz/task-manager-system/tree/master/task-manager-ui) 

 For more detail, standalone build and running project you can read the instruction defined on 
 [Task Manager Spring Backend Project](https://github.com/azizparmaksiz/task-manager-system/tree/master/task-manager) and 
 [Task Manager Angular Frontend Project](https://github.com/azizparmaksiz/task-manager-system/tree/master/task-manager-ui) .

## Requirements

For building and running the application you need:

- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

## Build and Run Project with Docker Compose

Go under ./task-manager directory and run `mvn clean install` to build jar file.
After build completed back to root folder.

Run `docker-compose up` to build and run docker images of  backend and frontend projects.

Navigate to `http://localhost:4200/` now you can see the angular project running. 

## Frontend Images

### Task List
![Task list](https://github.com/azizparmaksiz/task-manager-system/blob/master/images/tasklist.png)
### New Task Notification
![New Task Notification](https://github.com/azizparmaksiz/task-manager-system/blob/master/images/new-task-notification.png)
### Postpone Task
![Postpone Task](https://github.com/azizparmaksiz/task-manager-system/blob/master/images/postpone-task.png)
### Update Task
![Update Task](https://github.com/azizparmaksiz/task-manager-system/blob/master/images/update-task.png)


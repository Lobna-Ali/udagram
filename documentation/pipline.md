### Pipline Description
- Circle CI is triggered once a new code is pushed to the main branch
- The pipline will fail if any job failed
### Pipline WorkFlow
- docker image is installed
- steps is then triggerd and run the commands inside it
- Run FrontEnd install command
- Run BackEnd install command
- Run FrontEnd build command
- Run FrontEnd test command
- Run BackEnd build command
- Run BackEnd deploy command
- Run FrontEnd deploy command


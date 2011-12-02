# Web Project Template

## How to use this template

1. Clone the template to your computer using `git clone git@github.com:anatomic/Web-Project-Template.git`
2. Delete the git folder `rm -r -f .git`
3. Re-initialise git `git init`, `git add .`, `git commit -m 'start of the x project'`

The next steps are directly related to my personal project workflow so need to be adapted to fit yours.

4. Create a project on Chiliproject (this should probably have been done already and this process setup as a ticket!)
5. Make a note of the unique project number and create a bare repository on the SCM server:
  1. `ssh git@scm.xxx.co.uk`
  2. `git init --bare oom-xxx-project-name.git`
6. Add that bare repository as a remote `git remote add origin git@scm.xxx.co.uk:oom-xxx-project-name.git`
7. Push our new project to the server `git push -u origin master`

Et voila, you're all sorted!

Copyright (c) 2011 Ian Thomas
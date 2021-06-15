## some commands I am using debug node based app
### Debug node based  project

### Debug node based  project

- npx kill-port 3000   (for kill port if port already use )

          You can search on how to kill that process.
          For Linux/Mac OS search (sudo) run this in the terminal:
            
            $ lsof -i tcp:3000
            $ kill -9 PID
            On Windows:
            
            netstat -ano | findstr :3000
            tskill typeyourPIDhere 
            change tskill for taskkill in git bash
- npm cache clean --force  (if some node  package error installing)

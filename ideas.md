# multi-view
- tasks and todos are tagged with multiple aspects: priority, time, tags, category
- there is a separate directory and repo for each aspect of the tasks, with its own structure
- there's software that keeps these aspects synchronized, and a main repo that synchronizes all of them
    - but it doesn't provide a useful view
## structures
### time based
- today
- this week
- this month
- long term
- someday
### skill development
This can be high-level.
- Programming Languages
    - Python
    - TypeScript
        - deprioritize
    - Javascript
    - Lua
- DevOps Tools
    - Docker
        - deprioritize
    - Kubernetes
        - deprioritize
- Dev Tools
    - git
    - vim
    - tmux
- Web Development
    - CSS
        - deprioritize
    - React
        - deprioritize
### Tool Learning
- Add details for each
### Projects
- Consider adding "Miscellaneous" for tasks not related to specific projects
### Priority
- High Priority & Urgent (Due Today)
- High Priority (Due Soon)
- Medium Priority (Due Later)
- Low Priority (No Immediate Deadline)
### Workflow Stages
Use this structure to visualize the progression of tasks in your workflow
- Planning
- Development
- Testing
- Deployment
### Learning Resources
- Provide links to various learning resources and where I left off
- add estimated completion time for each
    - can maybe keep track of where my time is going
### complexity levels
- can be an aspect or breakdown for projects/tasks
- simple
- moderate
- complex
### dependencies
- independent tasks
- tasks with dependencies
    - on other tasks
- complex task chains
### progress tracking
- This is really an aspect of tasks.
- Use visual cues like colors or tags to highlight task status
- breakdowns
    - not started
    - in progress
    - stuck/blocked
    - completed
### Time investment
- This should be for daily tasks.
- Can be combined with progress tracking and dependencies.
- Use some notification/pomodoro technique so I dont continue without stopping
- breakdowns
    - Quick Tasks (<=15 mins)
    - Moderate Tasks (15 mins - 1 hour)
    - Time-Intensive Tasks (>1 hour)



# managing priorities
- I should have a global ordering of priorities and urgency

- breakdowns
    - High Priority & Urgent (Due Today)
    - High Priority (Due Soon)
    - Medium Priority (Due Later)
    - Low Priority (No Immediate Deadline)
## lifecycle
- https://en.wikipedia.org/wiki/Task_management#/media/File:TaskLifeCycle.png
    - state diagram
- https://web.archive.org/web/20180204000230/https://www.binfire.com/blog/2018/02/anatomy-of-a-task/
# look at tools
- task tracking
    - https://taskwarrior.org/docs
- project tracking
    - https://en.wikipedia.org/wiki/Assembla
- version control
    - https://gogs.io/
        - self-hosted git service
    - https://about.gitea.com/products/gitea
        - git hosting, code review, team collab, package registry, CI/CD
- workflow
    - https://airflow.apache.org/docs/apache-airflow/stable/index.html
    - Apache Kafka
    - https://www.prefect.io/opensource#prefect-cloud
    - https://conductor.netflix.com/
    - https://cadenceworkflow.io/
        - looks most promising
        - used with https://github.com/indeedeng/iwf
- task queues
    - celery
        - https://docs.celeryq.dev/
- templating
    - jinja
- message broker
    - rabbitMQ
    - redis
        - in memory queue
- parsing and compilation
    - antlr and bison
- cli string operations
    - https://github.com/abhimanyu003/sttr
- cli glue tools (TUI)
    - https://github.com/charmbracelet/bubbletea
- markdown rendering
    - https://github.com/charmbracelet/glamour
- markdown based slides
    - https://github.com/maaslalani/slides
    - https://sli.dev/
    - https://github.com/d0c-s4vage/lookatme
- tui stuff
    - https://charm.sh/libs/


# java tools
- https://www.dropwizard.io/en/stable/
    - all-in-one java framework

# topics to learn about
- webhooks

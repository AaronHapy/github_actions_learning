Workflow, Jobs, & Steps

Workflows:

- Are defined at the repository level
- Define which triggers actually start the workflow
- Are composed of one or more jobs.

Jobs:

- Are defined at the workflow level
- Define in which execution environment they are run (Linux, windows, mac)
- Are composed of one or more steps.
- Run in parallel by default.

Steps:

- Are defined at the job level
- Define the actual script or github action that will be executed.
- Run sequentially by default.

![workflows](images/img.png)


### Workflow Events
triggering workflows in multiple ways
There are many ways we can trigger GitHub workflows:

![img.png](img.png)

### Workflow Runners

virtual servers that execute jobs from workflows

![img_1.png](img_1.png)

### Actions

Custom applications to perform complex, frequently repeated tasks

![img_2.png](img_2.png)




![img_3.png](img_3.png)


![img_4.png](img_4.png)

![img_5.png](img_5.png)


![img_6.png](img_6.png)

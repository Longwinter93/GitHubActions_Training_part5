# GitHubActions_Training_part5
<br>In this task we learn about:
1. Conditions that control job execution:
    - If condition
    - Using check functions to have default behaviour
    - continue-on-error
2. Matrix strategy
    - Defining a matrix of different job configurations
    - Adding or removing individual combinations (including or excluding) 
    - Implemetning continue-on-error
3. Reusable workflow
    - We use reusable workflow by using for on values this workflow_call workflow. Thanks to it we can reuse steps and jobs from other workflows
    - Defining inputs, outputs and secrets that can be passed from the caller workflow and then used within called workflow

# techpuzzle8

## Problem Statement
You are the GCP infrastructure administrator and work with a development team that code an application that runs continuously.  The application runs in a Docker container running on a Compute Engine.  The source code of the applications is stored on GitHub.  You are hearing concerns that it takes too long for new versions of the application to be deployed.

Thinking about the story, you wonder if there is a mechanism in GCP such that when a change is made to the code in the GitHub repository, the latest version could be turned into a Docker image and quickly deployed into a Compute Engine.  How could this be done?

Cloud Build looks like a good candidate for detecting changes in GitHub.


## Solution
[PDF with solution](techpuzzle8-solution.pdf)
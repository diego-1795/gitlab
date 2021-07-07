# Image 1 - Gitlab
When you run the docker image, it must be possible to visit with the browser.
In Swagger has to exist a service controller that has to create a repository at Gitlab: this repository needs to have two branches (master & develop), and one tag (0.0.1).
You can use the oficial Gitlab API to do this action.
Data:
- Host: gitlab.localhost.com:9090

# Prerequisitos
Para la prueba se utilizara un

export GITLAB_HOME=$HOME/gitlab
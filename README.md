# Docker Git

A simple docker image that starts an SSH daemon to share a single Git project.

## Running and Connecting

Run the server with:

    docker run -ti -p 22022:22 docker-git

Clone the repo with:

    git clone ssh://git@localhost:22022/~/project.git


**NOT FOR PRODUCTION**

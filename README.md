A [Docker](https://www.docker.com) image for the [wget]
(https://www.gnu.org/software/wget/) file retrieval software package.

To use the container with a project, do the following:

* Copy the bin directory into your project.

* Ensure that your profile PATH includes `./bin` and that it takes priority over
any other directory that may include a composer executable:

`PATH=./bin:$PATH`

Now whenever you are in your project's directory, you can simply execute
`wget` as you would with a typical composer installation, and the command
will execute in the container instead:

`wget -h`

Docker Hub : https://hub.docker.com/r/chekote/wget/

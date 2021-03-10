## Original Java images are of big sizes:
	> openjdk                       11-jdk              604MB 
	> openjdk                       11-jdk-slim         384MB

With this dockerfile, it can be reduced to 107mb.

	> $ docker images
	> REPOSITORY      TAG            IMAGE ID       CREATED              SIZE
	> myjava          latest         22708cd3d054   8 seconds ago        107MB

For building, use below command:
>**docker build -t myjava .**

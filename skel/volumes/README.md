#Volumes folder

This folder is dedicated to host volumes for the services defined in the src folder.
There should be one folder per service, and each of them would contain as many folders as there are volumes for the service. Ideally folders should have the same name inside and outside of the container; but this is sometimes not possible (if more two volumes points to a folder with the same name).

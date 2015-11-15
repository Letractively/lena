To use a [Sesame](http://www.openrdf.org/) (2.1.3) HTTP repository, the following lines in the lena.properties file in `/WEB-INF/classes/` have to be changed:

`repository.type=http`

`server.url=http://localhost:8080/MySesameServerURL/`

`data.repository.id=myRepositoryID`

where you have to replace the Sesame server URL and the repository id, and change the repository.type to http.
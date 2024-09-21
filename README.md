README

This is a simple multi container app using 3 nginx docker containers

INSTALLATION

1) Clone the repo in your local machine
2) Install Docker
3) cd into the root directory named 'reposteria'
3) run the dockercompose file using: docker compose up --build -d 
4) Use either the browser or the cli to access both apps:


Example output:
```
[root@linux reposteria]# curl -L  http://localhost:8080/api/
<!DOCTYPE html>
<html>
<body>
<h1>Welcome to the API. This is Javier demonstrating I’m awesome at containers</h1>
</body>
</html>
```

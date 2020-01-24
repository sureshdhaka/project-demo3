# Movie-Search-REST-API

Create new Movie.
---
URL: http://localhost:8084/movies<br />
Request Type:POST<br />

```
Request Body: 
{
	"movie":"intersteller"
}
```
```
Response:
{
    "movie": "intersteller",
    "id": "5e29f75ffb0a2341e51cc9b7"
}
```

Get Movies List
---
URL: http://localhost:8084/search/prefix/limit/<br />
Request Type:GET<br />

```
Ex: http://localhost:8084/movies/search/J/2/
Response Body: 
[
    "inter",
    "interstellar"

]
```
# project-demo3

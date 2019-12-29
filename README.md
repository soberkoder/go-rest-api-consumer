# go-rest-api-consumer

Examples for cosuming a REST API in Go

***
### Setup and usage
```
Clone this repository to your go workspace and navigate to the project directory
```

```
$ go run main.go
```
That should give you the following output - We use the `todo` resource from [typicode online REST API](https://jsonplaceholder.typicode.com/) for consumption.
```
1. Performing Http Get...
API Response as String:
{
  "userId": 1,
  "id": 1,
  "title": "delectus aut autem",
  "completed": false
}
API Response as struct:
{UserID:1 ID:1 Title:delectus aut autem Completed:false}

2. Performing Http Post...
API Response as String:
{
  "userId": 1,
  "id": 201,
  "title": "lorem ipsum dolor sit amet",
  "completed": true
}
API Response as struct:
{UserID:1 ID:201 Title:lorem ipsum dolor sit amet Completed:true}

3. Performing Http Put...
API Response as String:
{
  "userId": 1,
  "id": 1,
  "title": "lorem ipsum dolor sit amet",
  "completed": true
}
API Response as struct:
{UserID:1 ID:1 Title:lorem ipsum dolor sit amet Completed:true}

4. Performing Http Delete...
API Response as String:
{}
```

***
### Tutorial

You can find the tutorial for this application at the [SoberKoder](https://www.soberkoder.com/) blog.

https://www.soberkoder.com/consume-rest-api-go/

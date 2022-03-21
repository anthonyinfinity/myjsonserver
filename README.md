# Create a JSON file on GitHub

For easily mocking JSON responses with [my-json-server.](https://my-json-server.typicode.com/)

Create a JSON file in a repo
```shell
github.com/anthonyininity/myjsonserver/main/db.json
```

```json
{
    "posts": [
        {
            "id": 1,
      "title": "hello"
    }
  ],
  "profile": {
      "name": "typicode"
  }
}
```

Get instantly a fake server, navigate to:

```
my-json-server.typicode.com/anthonyininity/myjsonserver/posts/1
```

```json
{
    "id": 1,
  "title": "hello"
}
```
# myjsonserver

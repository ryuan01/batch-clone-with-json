# batch-clone-with-json
Script to help clone all the forked versions of a git repo, reading from a json file.

## instructions
install ```jq``` on your computer 
```./mark src``` where src is json file with specific format

e.g.
```
{
  "instructor":
  {
    "name": "JohnDoe",
    "gitlink": "git@gitlab.com:JohnDoe/abc.git"
  },
  "students":
  [
    {
    "name": "hello",
    "gitlink": "hello"
    },
    {
    "name": "Bar Foo",
    "gitlink": "bar"
    }
  ]
}

```

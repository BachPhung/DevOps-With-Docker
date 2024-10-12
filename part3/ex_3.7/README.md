# At first:

```
docker image ls | grep "example-"
example-backend latest 79181492b7df About a minute ago 934MB
example-frontend latest 6a83101bdf8f 2 days ago 129MB
```

# After optimization:

```
docker image ls | grep "example-"
example-backend latest 78e9b91543bd 56 seconds ago 19.4MB
example-frontend latest e16bc180a5c1 About an hour ago 129MB
```

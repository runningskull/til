## Searching historical content

You can search all the content ever committed to a git project by doing 

```
git rev-list --all | xargs git grep <EXPRESSION>
```


## Searching commit messages

To search for some text in the project's commit messages:

```
git log --all --grep='<EXPRESSION>'
```

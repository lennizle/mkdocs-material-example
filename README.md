## Steps to reproduce

- install and run

```
pipenv install
mike deploy 1.0
mike deploy 1.1 latest
mike set-default latest
mike serve
```

- open localhost in browser
- navigate to http://localhost:8000/1.1/test/
- click on version switch 1.0

## Expected behavior:

- site navigates to http://localhost:8000/1.0/test/

## observed behavior

- site navigates to http://localhost:8000/1.0/

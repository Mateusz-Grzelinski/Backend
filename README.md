# Backend
Backend - FLASK microservice application

Run `python app.py`. You can make `GET` and `POST` calls to `localhost:5001` or use the GUI provided by the Frontend service (It needs to be run parallel with the Backend application).

To learn more about the application please check our Introduction to programming course on youtube:
https://www.youtube.com/watch?v=sCpVNizJbiE

## Run test

```python
python3 -m pytest --cov=. --cov-report xml:test-results/coverage.xml --junitxml=test-results/pytest-report.xml
# or 
pytest --cov=.
```

# Branches:
By selecting different branches you can get the sample code that you should have in you repository at the end of the selected block:

|Branches  | Block  | Description  | 
|---|---|---|
| main | CI/CD 1 | Basic application version |
| dockerfile | Docker 2 | Added docker container build files |

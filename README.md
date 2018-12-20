# https://github.com/serverless/serverless/issues/4638

```
sls deploy
# change serverless.yml to change variable1 to have value2
sls deploy # works for me
# change value in variable4.yaml to value5
sls deploy # works for me
# change ssm variable
sls deploy # works for me
# not sure how to test {Ref: ...} in a way that wouldn't update the stack for other reasons anyway
```

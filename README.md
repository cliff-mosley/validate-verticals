# validate-verticals

Basic validation of the verticals data provided by Finance

## Steps to configure

Assumes you're starting from a new directory but have pipenv installed

```console
pipenv install great_expectations
pipenv shell

great_expectations init
great_expectations checkpoint run second_checkpoint

```

## Other useful commands

```console
great_expectations suite scaffold verticals
great_expectations suite edit verticals
great_expectations checkpoint new <checkpoint_name> verticals
```

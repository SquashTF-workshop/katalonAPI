Ce projet Katalon est structuré de la manière suivante :

```
Everything (TestSuiteCollection)
|
|-AllParam (TestSuite)
  |
  |-Parameter/Community (TestCase)
  |
  |-Parameter/Premium (TestCase)
  |
  |-Parameter/ExistingParameter (TestCase)
|
|-NoParamOK (TestSuite)
  |
  |-ForecastOK (TestCase)
  |
|
|-NoParamKO (TestSuite)
  |
  |-AirPollIncorrectLocator (TestCase)
  |
  |-History404 (TestCase)
  |
  |-HistoryKO (TestCase)
```

Les paramètres attendus pour community sont les suivants :

DS_param : 800

DSNAME : Clear

TC_CUF_icon : 01n

Les paramètres attendus pour premium sont les suivants :

CPG_CUF_humidity : 100

IT_CUF_sealevel : 1031.04

TS_CUF_grndlevel : 1021.39


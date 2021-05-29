## Checker
CLI-utility, pings sites form csv-file, placed in ```/data```, e.g. *rails.csv*

### Set up
```
bundle install
make test
```

### Usage
run ```./bin/checker --help``` for available options

Example: ```./bin/checker --exclude-solutions --parallel=5 filter=price```

See ```Makefile``` for other examples

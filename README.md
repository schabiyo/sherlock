## sherlock

Seach tool for MongoDB Atlas and Cloud Manager.


## Installation


For Mac OS using Homebrew:

```
brew install schabiyo/mongo/sherlock
```

## Usage

Use environment variables to save your credentials:

```
export SB_ATLAS_USERNAME=username
export SB_ATLAS_APIKEY=key
```

To see the available organisation:

```
sherlock orgs
```

To view all projects :

```
sherlock projects
```


To view projects within one organization:

```
sherlock projects -o ORG-NAME
```

To view all clusters :

```
sherlock clusters 
```


### CLI flags and environment variables

In addition to using env vars, you can use CLI flags. See `sherlock -h` and `sherlock <command> -h` for more details.

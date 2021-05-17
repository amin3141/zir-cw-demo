# Readme

The source code in this repository demonstrates semantic search over a child
welfare case notes using ZIR Semantic Search.

## Data

`/src/main/resources`, Contains sample case notes.

## Programs

## cases.py

This program provides a line-oriented interpreter for running queries against a
corpus of case notes. Here's a sample session:

```
$ ./src/main/cases.py\
    --customer-id 1526022105\
    --corpus-id 14\
    --app-client-id 20hestglli47sd563mbq01ha9e\
    --auth-domain https://zir-prod-1526022105.auth.us-west-2.amazoncognito.com
```

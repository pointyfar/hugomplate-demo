# Hugo + Gomplate = Good Stuff

Head over to the [gomplate docs](https://docs.gomplate.ca/) or [Hugo docs](https://gohugo.io/documentation/) for details about those projects.

Please treat this as a Proof of Concept rather than a proper Tutorial. Probably not for absolute beginners.

## What this is

A project demonstrating what happens when you combine `gomplate` and `hugo`. 

I am using `gomplate` to populate the `/content/` directory from a datasource. Hugo does the rest.

## How to use

The following examples are included:

### API datasource

```
gomplate --config api.yaml
```

`sample-outputs/api/`

### Local JSON file datasource

```
gomplate --config localjson.yaml
```

`sample-outputs/localjson/`

### CSV file datasource

```
gomplate --config localcsv.yaml
```

`sample-outputs/localcsv/`


### Hugo Demo

Navigate to `/hugo-demo/` and run `gomplate`

Run `hugo server`

## Notes

Not a Hugo dev. Not a gomplate dev. Not really a Go dev at all.

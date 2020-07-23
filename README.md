# Hugo + Gomplate = Good Stuff

Head over to the [gomplate docs](https://docs.gomplate.ca/) or [Hugo docs](https://gohugo.io/documentation/) for details about those projects.

Please treat this as a Proof of Concept rather than a proper Tutorial. Probably not for absolute beginners.

## What this is

A project demonstrating what happens when you combine `gomplate` and `hugo`. 

I am using `gomplate` to populate the `/content/` directory from a datasource. Hugo does the rest.

## How to use

The following examples are included:

### Hugo Demo

Navigate to `hugo-demo` and run `gomplate`

This will populate `hugo-demo/content/posts/` with posts from `https://jsonplaceholder.typicode.com/posts`.

Run `hugo server` to see it as a Hugo website in action.

### API datasource

```
gomplate --config api.yaml
```

This will populate `outputs/api` with posts from `https://jsonplaceholder.typicode.com/posts`. 

Sample output can be found at `sample-outputs/api/`

### Local JSON file datasource

```
gomplate --config localjson.yaml
```

This will populate `outputs/localjson` with `.md` posts from `sources/datasource.json`. 

Sample output can be found at `sample-outputs/localjson/`

### CSV file datasource

```
gomplate --config localcsv.yaml
```

This will populate `outputs/localcsv` with `.md` posts from `sources/datasource.csv`. 

Sample output can be found at `sample-outputs/localcsv/`


## Notes

Not a Hugo dev. Not a gomplate dev. Not really a Go dev at all.

Big thanks to the people behind [Hugo](https://github.com/gohugoio/hugo/) and [gomplate](https://github.com/hairyhenderson/gomplate/) for developing these awesome products.

## License

MIT.
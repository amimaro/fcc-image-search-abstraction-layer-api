# FreeCodeCamp - Backend Challenges
## API Projet: Image Search Abstraction Layer
### User stories:
1. I can get the image URLs, alt text and page urls for a set of images relating to a given search string.
2. I can paginate through the responses by adding a ?offset=2 parameter to the URL.
3. I can get a list of the most recently submitted search strings.
## Example usage:
```url
https://fcc-api-4.glitch.me/api/imagesearch/lolcats%20funny?offset=10
https://fcc-api-4.glitch.me/api/latest/imagesearch
```
## Example output - search:
```json
{ { "snippet": "", "url": "", "context": "", "thumbnail": "" } ... }
```

## Example output - latest:
```json
{{ "term": "", "when": "" } ... }
```

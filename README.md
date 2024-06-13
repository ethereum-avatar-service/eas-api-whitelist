# eas-api-whitelist
Collection whitelist for the official eas API

## How to submit a collection for verification
Open a new issue on this repo and include the necessary metadata for the collection. Example:

```json
{
  "polygon": [
    {
      "contract": "0xeb959a715dfffe6f82f4605533982c4859cb14fe",
      "name": "Reddit Starter Pack x Reddit Collectible Avatars",
      "author": "reddit inc.",
      "website": "https://www.reddit.com",
      "opensea": "https://opensea.io/collection/reddit-starter-pack-x-reddit-collectible-avatars"
    }
  ]
}
```

Notice here that `polygon` should be changed to whatever EVM network the collection lives on.

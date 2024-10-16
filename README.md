
## Build Documentation

To build the documentation, make sure the frontend is running locally at `http://localhost:3000` and run the following command:

```
curl http://localhost:3000/api/openapi -o openapi.json && npx @redocly/cli build-docs openapi.json && mv redoc-static.html index.html
```

Commit your changes and push to main; the website should be updated now.

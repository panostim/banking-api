# Blip Banking - API Documentation

This repository contains the OpenAPI specification for the fictional BNPL (Buy Now Pay Later) solution named **Blip**. The API can be explored using Swagger UI.

### Viewing Online

The documentation is deployed in Vercel and publicly accessible in: 
[`https://banking-r19wjogen-panostims-projects.vercel.app/`](https://banking-r19wjogen-panostims-projects.vercel.app/)

### Viewing in a Browser locally

Serve the `docs` folder with any static web server, then open `index.html` in a browser. For example using Python:

```bash
python3 -m http.server --directory docs 8000
```

Then navigate to <http://localhost:8000> to view the interactive API documentation.

### API Overview

The specification includes endpoints for creating and retrieving credit sessions and payments, canceling payments, and issuing refunds. Each operation documents common error responses (400, 404, 500) with example error messages.

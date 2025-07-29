# MicroLoan API Documentation

This repository contains the OpenAPI specification for the fictional **MicroLoan** BNPL (Buy Now Pay Later) solution. The API can be explored using Swagger UI.

## Documentation

The OpenAPI specification can be found at [`docs/openapi.yaml`](docs/openapi.yaml). An HTML page that loads Swagger UI is provided in [`docs/index.html`](docs/index.html).

### Viewing in a Browser

Serve the `docs` folder with any static web server, then open `index.html` in a browser. For example using Python:

```bash
python3 -m http.server --directory docs 8000
```

Then navigate to <http://localhost:8000> to view the interactive API documentation.

### API Overview

The specification includes endpoints for creating and retrieving credit sessions and payments, canceling payments, and issuing refunds. Each operation documents common error responses (400, 404, 500) with example error messages.
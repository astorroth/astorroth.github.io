# Astor Roth - Artist Portfolio

This is the portfolio website for Astor Roth, hosted on GitHub Pages.

## Local Development

To serve the site locally, you can use a simple static server.

If you need a development environment using Docker:

```bash
docker run -it --rm \
    -v $(pwd):$(pwd) \
    -w $(pwd) \
    -p 3000:3000 \
    -p 6006:6006 \
    node:22 bash
```

### Using npm `serve`

1. Install `serve` globally (if not already installed):
    ```bash
    npm install -g serve
    ```

2. Run the server from the project root:
    ```bash
    serve
    ```

3. Open your browser at the URL shown (usually http://localhost:3000).


# Teaching Talk - Trees

This repo creates a website for use in a teaching talk on feature engineering.

It relies on the `quarto-live` extension, which is a WASM version of the R language and allows you to run R code in your browser without needing to install R on your system.

To install the extension, run the following command in this directory:

```bash
quarto add r-wasm/quarto-live
```

After this, `quarto render` will create a website in the `docs` directory.

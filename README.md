# CRD Schemas

These are schemas that are being generated from within my home cluster along using datree's crd-extrator tool.

For convenience I have also added the schemas from the [CRDSs-catalog](https://github.com/datreeio/CRDs-catalog) repository.

I use these schemas with my neovim config to provide autocompletion and syntax highlighting for custom resources.

The process to refresh the above gets ran every 2 weeks, copying from CRDs-catalog and running the crd-extractor tool, prioritising the crd-extractor tool results. It will first rsync (overwrite) files using files from CRDs-catalog and then rsync (overwriting) files from crd-extractor.

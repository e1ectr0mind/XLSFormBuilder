# XLSFormBuilder

This repository contains a collection of XLSForm blocks stored in the `forms/` directory.
The `xlsform_builder.py` script allows you to combine these blocks into a single form.

## Usage

```
python xlsform_builder.py block1 block2 -o output.xlsx
```

Each block argument may be a path to an `.xlsx` file or the base name of a file
located in the `forms/` directory (the `.xlsx` extension is optional).

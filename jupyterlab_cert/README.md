# JupyterCon Certificate

JupyterCon Certificate extension


## Prerequisites

* JupyterLab

## Installation

```bash
jupyter labextension install jupytercon_cert
```

## Development

For a development install (requires npm version 4 or later), do the following in the repository directory:

```bash
npm install
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```

## Example file. 

The extension renders file with `.json` or `.cert.json` extension, that have the `given` and `event` field.
Example:

```
{
  "given": "Jason Grout",
  "event": "JupyterCon 2018"
}
```

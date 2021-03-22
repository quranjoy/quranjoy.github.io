# Rebuild website when working on it
Run command `pelican -r`

# Publish to docs directory
Rename by deleting docs and renaming output to docs.
- Run command from main project folder: 

```
    rm -rf docs
    mv output docs 

```

# How to run in your local browser
Run from the output directory: 
`python3 -m http.server`

View at http://localhost:8000
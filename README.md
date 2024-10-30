## Installation
By default, changes to the markdown file in this repository trigger a github action that builds a pdf from the markdown source and commits the file. 

To enable the comitting of this file back to this repository click on Settings > Actions > General and (under workflow permissions) select "Read and write permissions" & "Allow GitHub Actions to create and approve pull requests".

```bash
# or run locally:

# Install mdpdf globally
npm install -g mdpdf@3.0.1

# Build pdf from markdown locally
mdpdf cv.md --style=styles.css --border-top=12mm --border-bottom=0mm --border-left=4mm --border-right=4mm
```

### About
What's the point in using markdown for a cv? 

If you know HTML, it's easier to adapt than LaTeX (and doesn't have the huge LaTeX compiler), you can comment out information that isn't relevant for a particular job and you can easily version content using git/github. 

This is an opinionated cv template to help catalyse that process.

```
opinionated-markdown-cv-template
  ├─ README.md
  |   └─ You are here.
  ├─ cv.md
  |   └─ Opinionated markdown cv template replace [] with your information.
  ├─ cv.pdf
  |   └─ PDF cv output genereated my mdpdf.
  └─ styles.css
      └─ Custom styling for HTML elements in the cv markdown file.
```

## Acknowledgements
Heavy lifting done by [mdpdf](https://github.com/bluehatbrit/mdpdf).
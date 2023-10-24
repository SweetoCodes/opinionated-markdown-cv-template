## Installation

```bash
# Run Locally
# Install mdpdf glboally
npm install -g mdpdf@3.0.1

# Build pdf from markdown locally
mdpdf cv.md --style=styles.css --border-top=12mm --border-bottom=1mm --border-left=4mm --border-right=4mm
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
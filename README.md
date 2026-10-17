# Python Learning Path

A free, self-paced Python tutorial built from this repository's course notes, Jupyter notebooks, exercises, and project resources. The homepage brings the material together in a guided path from the fundamentals to advanced topics and app frameworks.

## View the website

Open [`index.html`](./index.html) in a browser, or publish the repository with GitHub Pages:

1. Push the repository to GitHub.
2. Open **Settings → Pages** for the repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/(root)` folder, then save.
5. When the deployment finishes, open the Pages URL shown in the settings.

The site is plain HTML, CSS, and JavaScript. It has no build step, package installation, or server-side requirements.

## Read files in the browser

Select a lesson or a file in **Browse course files in your browser** to open the reader. The reader supports:

- PDF files, using the browser's built-in PDF viewer
- Markdown files, rendered as readable pages
- Python files, displayed as source code
- Jupyter notebooks, displayed as Markdown, code cells, and saved text/image outputs
- HTML files, displayed in a sandboxed preview

Notebook code is never executed by the site. To run a notebook, download it and open it in Jupyter. The reader fetches course files, so Markdown, Python, and notebook previews require the site to be served over HTTP or HTTPS; opening `index.html` directly with a `file://` URL may prevent those previews from loading. GitHub Pages serves the files correctly. Word documents (`.doc` and `.docx`) remain linked as downloads because browsers do not natively display them.

## Learning path

The homepage links to the course material in the `5.python basic to Advance/` folder and suggests this order:

1. Getting started and Python fundamentals
2. Operators, conditionals, and loops
3. Strings and collections
4. Functions, modules, and packages
5. File handling and exceptions
6. Object-oriented programming
7. Regular expressions, web scraping, and pickling
8. Databases, advanced Python, Streamlit, Flask, and FastAPI

Use the search box on the homepage to filter lessons by topic. The **Practice and project resources** section links to exercises, interview questions, project ideas, a cheat sheet, and additional class practice.

## Course materials

- `5.python basic to Advance/` — syllabus, lesson documents, notebooks, projects, and examples
- `class_practice/` — supplementary exercises, notebooks, and sample data
- `Extras/` — presentation slides, Python scripts, and a cheat sheet

Notebook files (`.ipynb`) can be read in the site, or downloaded and opened in Jupyter Notebook, JupyterLab, or a compatible editor. Lesson documents and presentations can be opened with compatible office software.

## Contributing

Keep the site static and dependency-free. When adding course materials, update the relevant links in `index.html` and verify that each link points to a tracked file in the repository.

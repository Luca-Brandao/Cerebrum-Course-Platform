# Cerebrum Online IT Courses

One educational website, developed through three coursework stages. I started with static HTML and CSS, added JavaScript interactions, then connected the frontend to Flask and Express APIs.

**Author:** Luca Brandao  
**Coursework:** WST262, STADIO Higher Education

## Development stages

| Stage | What changed | Documentation |
| :--- | :--- | :--- |
| SS1 | Static course pages, navigation, contact layout and CSS styling. | [Setup and features](ss1/README.md) |
| SS2 | Responsive pages, JavaScript interactions, forms and testimonials. | [Setup and features](ss2/README.md) |
| SS3 | Bootstrap frontend, Flask course/contact API and an Express testimonials service. | [Setup and features](ss3/README.md) |

Each folder is a complete stage with its own source, assets and detailed README. They run independently. **SS3 is the most complete version**; SS1 and SS2 show how the project developed.

## Run the latest stage

Install Python 3.10+ and Node.js 18+ first. From this repository's root:

```sh
cd ss3
python -m venv .venv
```

Activate the environment (`.venv\Scripts\activate` on Windows, or `source .venv/bin/activate` on macOS/Linux), then run:

```sh
python -m pip install -r requirements.txt
npm ci
python app.py
```

In a second terminal, open this repository's `ss3` folder and run `npm start`. Visit **http://127.0.0.1:5000**. Keep both terminals running; Express uses port 3000. The [SS3 README](ss3/README.md) explains the API endpoints, usage, data files and troubleshooting.

For the earlier stages, open `ss1/Html/home.html` or `ss2/Html/home.html`. Their READMEs also explain the optional local HTTP server.

## What I practised

Page structure and styling, responsive layouts, DOM events, client-side validation, Fetch requests, API design and local JSON persistence. This is coursework for a fictional course provider, with fictional sample identities and example.com contact details.

## Project notes

The original implementations remain in their stage folders. Sample names, matching image filenames and contact details were updated consistently for the public portfolio. Machine-specific paths were corrected, generated submissions were removed and runtime fixes are documented in each stage's README.

This is a local demonstration. It has no production authentication, enrolment or payments. SS3 requires both servers, and Bootstrap assets require an internet connection. JSON file storage is intended for coursework use.

[My GitHub profile](https://github.com/Luca-Brandao) · [LinkedIn](https://www.linkedin.com/in/luca-brandao-a90961352/)

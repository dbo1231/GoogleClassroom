# Google Classroom

A single-file Windows-inspired web OS UI.

## GitHub Pages

1. Create a **public** GitHub repository.
2. Upload `index.html` and `.nojekyll`.
3. Go to **Settings → Pages**.
4. Set **Source** to `Deploy from a branch`.
5. Select **main** and **/(root)**.
6. Save.
7. Open the GitHub Pages URL shown by GitHub.

## Project structure

```text
GoogleClassroom/
├── index.html
├── .nojekyll
└── README.md
```

## Important

This project is client-side only. The PIN in the original source is not secure authentication because it is stored in JavaScript.

The built-in browser uses the external WebFuse iframe bridge from the original file. Its availability and whether individual websites allow iframe embedding are controlled by those external sites/services, not GitHub Pages.

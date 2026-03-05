# Portfolio Website

Static HTML/CSS personal website. Three pages: Home, About, Portfolio.

## File structure

```
portfolio/
├── index.html
├── about.html
├── portfolio.html
├── css/
│   └── style.css
└── assets/
    ├── icons/
    │   └── favicon.ico          ← your favicon (32×32 px .ico or .png)
    ├── images/
    │   ├── profile-placeholder  ← hero photo on Home page (portrait, ~600×800)
    │   ├── about-placeholder    ← photo on About page (portrait, ~400×530)
    │   ├── project-1-placeholder← project screenshot/diagram (16:9)
    │   ├── project-2-placeholder
    │   ├── project-3-placeholder
    │   ├── project-4-placeholder
    │   ├── project-5-placeholder
    │   └── project-6-placeholder
    └── resume.pdf               ← your CV (linked from About page)
```

## Assets to replace

| Placeholder                      | Used in        | Recommended size |
|----------------------------------|----------------|------------------|
| profile-placeholder.jpg          | index.html     | 600 × 800 px     |
| about-placeholder.jpg            | about.html     | 400 × 530 px     |
| project-{1-6}-placeholder.jpg    | portfolio.html | 800 × 450 px     |
| favicon.ico                      | all pages      | 32 × 32 px       |
| resume.pdf                       | about.html     | —                |

## Text to personalise

Search for `[` in any HTML file to find all placeholder text you need to fill in:
- `[University Name]`
- `[Company]` / `[Company / Institution]`
- `[Year]`
- `[Your thesis title here]`
- `[Supervisor Name]`
- `your-handle` (GitHub / LinkedIn URLs)
- `hello@janedoe.com`

## Deployment

Drop the whole folder onto **Netlify** (drag-and-drop deploy) or push to
a GitHub repo and enable **GitHub Pages** — no build step needed.

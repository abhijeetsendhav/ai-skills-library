# AI Skills Library

Claude skill packages used across Hi-Tech Digital Solutions projects. Each
folder is a self-contained skill (a `SKILL.md` with front matter, plus any
reference files or scripts it needs) that can be installed into a project
with the [skills CLI](https://www.npmjs.com/package/skills):

```
npx skills add <owner>/<repo> --skill <folder-name>
```

These are also published in the internal **AI Skills Directory** at the
company, where they can be browsed, reviewed and installed with one click.

## Skills

| Folder | Category |
| --- | --- |
| `apple-design` | Design & UI |
| `design-mobile-apps` | Authentication & Access |
| `frontend-design` | Design & UI |
| `login` | Authentication & Access |
| `scrape-zyte-login` | Authentication & Access |
| `supabase-postgres-best-practices` | Documentation & Writing |
| `web-design-guidelines` | Design & UI |
| `website-login` | Authentication & Access |

## Contributing a new skill

1. Create a new folder with a `SKILL.md` (front matter + body) and any
   supporting files.
2. Open a pull request.
3. Once merged, publish it through the AI Skills Directory so the rest of
   the company can discover and install it.

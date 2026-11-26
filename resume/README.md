# CV sources

The four CVs as [resume-generator](https://github.com/xMuramasa/resume-generator) JSON:

| File                   | Version                 |
| ---------------------- | ----------------------- |
| `en-resume-short.json` | English, 1 page         |
| `en-resume-long.json`  | English, 2 pages        |
| `es-cv-short.json`     | Español, 1 página       |
| `es-cv-long.json`      | Español, 2 páginas      |

Edit the JSON (here or on github.com). On every push to `main` that touches this folder, the
[CV workflow](../.github/workflows/cv.yml) builds the PDFs with resume-generator, fails if a short CV runs past one
page or a long one past two, and replaces the PDFs on the [`cv` release](https://github.com/xMuramasa/xMuramasa/releases/tag/cv).
The links in the profile README point there.

Locally: `python3 main.py` in resume-generator, with `RESUME_SRC` pointing at this folder.

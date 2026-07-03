# AGENTS.md

## How to Work in This Repository

- This is a small Hugo site. Data lives in `data/`, templates in `layouts/`, styles in `static/css/report.css`, and source notes and spreadsheets in `input/`.
- Use `input/ЗАПРОС.md` as the source of truth when editing semantic data, but do not rewrite it into agent instructions.
- Do not change `id` values in `data/criteria.yaml` unless you also update the references to those `id` values in `data/models/*.yaml`.
- The maximum rating is calculated in `layouts/_default/comparison.html` from the sum of `criteria.weight`; do not store it as a separate YAML field.
- After YAML edits, verify that the files parse and that models have no missing or extra criteria.
- If Hugo is available, run `hugo` or check the page through an already running `hugo server`.
- Do not edit `public/` manually: it is build output.
- Do not add new dependencies or generators unless they are explicitly needed.

## Data Style

- Data and UI text in this repository are in Russian.
- Wording in `data/criteria.yaml` must be verifiable: describe what disqualifies a choice and how to check it.
- Do not mix criticality levels with slash labels such as `High/Bonus` when one clear level can be chosen.
- Criteria with `priority: "Пофиг"` must have `weight: 0` if they truly do not affect the rating.

## UI Style

- Tables should be dense and readable.
- Keep utility columns such as `Крит` and `Вес` narrow; give the space to longer text.
- Do not make headers or navigation sticky unless explicitly requested.
- Do not add decorative blocks unless they carry information.

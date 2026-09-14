# Pundo landing page

Single-file, mobile-first landing page for the Pundo helper project.

## What it does
- Focuses version 1 on Filipino domestic helpers already working in Singapore.
- Uses a short 4-step form so the page does not feel like a long survey.
- Collects work history, years in Singapore, employers, actual duties, salary, remittance, debt, savings, emergencies, recurring costs, and future goals.
- Avoids generic “would this be useful?” validation questions.
- Does not store form responses on the website.
- Opens WhatsApp to +65 8034 6968 with the answers prefilled. The helper decides whether to send them.

## GitHub Pages
Recommended organization repository:
`PundoPH/PundoPH.github.io`

Place `index.html` at the repository root, then enable GitHub Pages for the default branch if Pages is not already active.

The resulting organization site should be:
`https://pundoph.github.io/`

## Edit the WhatsApp number
In `index.html`, search for:

`const WHATSAPP_NUMBER = "6580346968";`

Use digits only, including the country code.

# PCC College Liturgical Ministries — Constitutional Convention Website

A complete, responsive, offline-capable (after fonts load) local website for the proposed 45-day Constitutional Convention. **No calendar dates are displayed.** All scheduling is by convention day number.

## Run locally

### XAMPP (Windows)
1. Extract the `pcc-convention-site` folder into `C:\xampp\htdocs\`.
2. Open XAMPP Control Panel and start **Apache**.
3. Visit `http://localhost/pcc-convention-site/`.

### VS Code / Python alternative
In the extracted folder run:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

### PHP alternative

```sh
php -S localhost:8000
```

## Features
- Responsive sidebar dashboard and custom logo
- Complete Day 1–45 roadmap with searchable, filterable activity checklist
- Eight detailed major-session agendas with Holy Rosary and Holy Mass
- Committee and delegate roster with representation and working groups
- First and Second Reading overview with amendment register and statuses
- Document deliverables checklist and reference register
- Spiritual program, assignments, and liturgical safeguards
- Printable session agendas and document checklist
- Roadmap CSV export and JSON backup / restore
- Browser localStorage persistence (no account, server database, or network sync)

## Important limitations
- This is a **single-browser local planning tool**. Data entered on one device is not automatically shared with other users.
- No actual files are uploaded in the document register; enter references or file locations instead.
- No secure electronic voting, credential verification, multi-user authentication, or institutional approval workflow is provided.
- All schedules and governance details are proposals pending discernment, committee action, and PCC institutional approvals.
- Google Fonts may load when online; the site uses system fallbacks offline.

## Files
- `index.html`: entry page
- `assets/styles.css`: responsive visual design
- `assets/app.js`: data, pages, and interactivity
- `assets/convention-logo.png`: event logo

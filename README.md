# Spend Sankey

Visualize spend by **Department** and **Person** from an Excel file. Full view: Total Spend → Departments → People; click a department node to drill down to people in that department.

---

## Share with others (no install)

**Use this file:** **`Spend-Sankey.html`**

- Double-click `Spend-Sankey.html` to open it in your browser (or right-click → Open with → Chrome/Edge).
- Drag & drop your Excel file (or click Choose File). No Node, npm, or Git required.
- To share: send the **`Spend-Sankey.html`** file (and your Excel if they need to use their own data). Recipients only need a browser and the same Excel columns: **Department**, **Person**, **Annualized**.

---

## Excel format

First sheet must have columns:

- **Department**
- **Person**
- **Annualized** (numeric spend amount)

---

## Optional: run as dev app

If you prefer the npm version:

```bash
npm install
npm run dev
```

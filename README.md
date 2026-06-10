# LUME Inventory OS — Rebuilt

A rebuilt mobile-first inventory app for LUME stock management.

## Main workflows

- First owner setup, then login only.
- Admin can create users, add products, edit products, delete products, import/export backup.
- Sales users can view stock and sell only from Socrate.
- Stock is separated by hub: Mediouna and Socrate.
- New BL / Receive lets admin select many products in one operation and add quantities with BL number, date, destination hub and note.
- Every stock movement is saved in product history: receive, sale, transfer, adjustment, delete.

## Important

This is still a static GitHub Pages/localStorage app. It is good for a local lightweight workflow, but it cannot synchronize stock between different phones/browsers by itself and cannot truly prevent a fresh browser from first setup without a backend.

For a real company-grade system, connect this frontend to Supabase/Firebase with authentication and a shared database.

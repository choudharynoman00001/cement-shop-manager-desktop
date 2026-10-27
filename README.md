# Cement Shop Manager - Windows Setup

Retail cement shop software for one shop computer: products and brands, purchases and suppliers, stock, sales (cash, credit, mixed), customer and supplier balances, returns, cash close, reports, backups. Urdu and English screens, amounts in PKR.

This repository only carries the Windows installer. The app source is private.

## Status

The Windows installer is not released yet. There is nothing to download here for now.

## What you should know

- The app runs on this computer only, over plain local HTTP (127.0.0.1). It is not a website and needs no internet.
- It is built for one shop PC. It is not made for several computers sharing one database.
- Your data stays in `%APPDATA%\Cement Shop Manager\data`. Uninstalling does not delete it.
- Make backups from the app and keep a copy on another disk or USB. Test a restore on a copy, not on your live data.
- Tested on a Windows test computer with made-up data only (installer, login, sales, stock, backup and restore, Urdu PDF and Excel export, uninstall keeping data). Not tested on every PC, with a receipt printer, or with a barcode scanner.
- PDF reports with Urdu use the fonts installed on your PC. If a PDF cannot be made, the app says so and does not save a wrong file. Excel export is available. PDF table headings are still in English field names.
- Tax, credit limits and costing rules are your shop's own decisions. Check them with your accountant before you rely on the numbers.

Support: https://alphablue.digital

Developed by Chaudhry Noman - Powered by Alpha Blue Digital

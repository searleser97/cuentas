# Cuentas

Static page to assign each credit-card transaction to Sergio / Abi / Joint, backed by a private Google Sheet.

- Signs in with Google (OAuth Web client, token flow). No secrets in this repo: the OAuth client ID and sheet ID in `config.js` are public identifiers; access is enforced by Google sign-in and the sheet's sharing settings.
- Reads and writes the `Transacciones` tab through the Google Sheets API from the browser.

# Troubleshooting

### Scenario: Authentication uses the wrong GitHub or Fabric account

Your browser might automatically reuse an existing work account or Enterprise Managed User session. This can authenticate workshop tools with the wrong account without displaying an account selection prompt.

#### Solution

1. Open an incognito or private browser window. Alternatively, create a separate browser profile for the workshop.
2. Keep this window or profile open for the entire study.
3. Use this window for every authentication link:
   - For GitHub, sign in with the personal GitHub account that has the workshop license. Enterprise Managed User accounts won't work.
   - For Fabric, sign in with the workshop-provided Fabric account.
4. When a command-line tool opens an authentication page in your default browser, copy the authentication URL and open it in the incognito window or workshop browser profile instead.

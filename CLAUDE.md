# Project Rules

## Shortcuts

### "kill me"
When the user says "kill me":
1. Kill all running Node/Next.js processes on ports 3000 and 3001 (`lsof -ti:3000,3001 | xargs kill -9`)
2. Start a fresh dev server on port 3000: `npx next dev -p 3000 --turbo`
3. Confirm the server is running at http://localhost:3000

# Copilot Instructions for AI Agents

## Project Overview
- This is a React project bootstrapped with Vite, located in the `/src` directory.
- The entry point is `src/index.jsx`, with the main app component in `src/App.jsx`.
- Static assets are in `/public` (e.g., `favicon.ico`, `manifest.json`).

## Build & Run Workflows
- **Development server:** Use `npm start` to run Vite on port 3000 (auto-switches if busy). Output is at `http://localhost:3000/`.
- **Testing:** Use `npm test` to run tests with Vitest. Test files are in `src/` and use the `.test.jsx` extension.
- **Build:** Use `npm run build` to create a production build in `dist/`.
- **Preview:** Use `npm run preview` to serve the production build locally.

## Testing Details
- Tests use Vitest and Testing Library (`@testing-library/react`, `@testing-library/jest-dom`).
- The test environment is configured as `jsdom` in `vite.config.js`.
- Global test setup is in `src/setupTests.js`.

## Project Conventions
- React components use `.jsx` and `.css` files in `/src`.
- Main CSS files: `src/App.css`, `src/index.css`.
- Use functional components and hooks (see `App.jsx`).
- No custom routing or state management libraries are present by default.

## Integration Points
- Vite plugins configured in `vite.config.js` (currently only `@vitejs/plugin-react`).
- No backend/API integration in the starter; add API calls in components as needed.
- Static assets referenced via `/public`.

## Patterns & Examples
- Component structure: `function App() { ... } export default App;`
- Test example: `App.test.jsx` uses Testing Library to verify rendering.
- Entry point: `ReactDOM.createRoot(document.getElementById('root')).render(<App />)` in `index.jsx`.

## Troubleshooting
- If port 3000 is busy, Vite auto-switches to the next available port.
- For build/test errors, check `vite.config.js` and dependencies in `package.json`.

## Key Files
- `src/App.jsx`, `src/App.test.jsx`, `src/index.jsx`, `vite.config.js`, `package.json`, `README.md`

---

Update this file as project structure or conventions evolve. For questions, see the README or Vite documentation.

# Urgent Decision Maker

A "Yes / No" wheel — a fun random choice picker component built with React. Add custom options (e.g. "What to eat?"), spin the animated wheel, and get a randomly selected answer. Great for settling frequent everyday dilemmas.

> Note: this repo currently holds a single React component file. See "Running" below to embed it in a project.

## Features

- Animated spinning wheel with random selection logic
- Custom options — add and remove your own choices (e.g. "Yes", "No", "Maybe")
- Spinner disables during the spin; winner is highlighted
- Zero dependencies on storage/auth — fully client-side

## Tech Stack

- React (hooks: `useState`, `useRef`, `useEffect`)
- shadcn/ui primitives (`Button`, `Input`, `Card`)
- Lucide icons (`Plus`, `X`)
- TypeScript

## Running

This is a standalone component (file: `Urgent Decision Maker`). To use it in a Vite + React project:

1. Install dependencies:
   ```bash
   npm install react lucide-react
   # plus shadcn/ui setup for @/components/ui/{button,input,card}
   ```
2. Copy the `Urgent Decision Maker` file into your project's component tree (rename to `.tsx`).
3. Render it:
   ```tsx
   import DecisionMaker from "./components/UrgentDecisionMaker";
   // ...
   <DecisionMaker />
   ```

## Project Structure

```
Urgent-Decision-Maker/
├── Urgent Decision Maker   # The React component (TSX/JSX source)
├── LICENSE
└── README.md
```

## License

See `LICENSE`.

## Built by

**Built by Girish Lade** — [ladestack.in](https://ladestack.in)

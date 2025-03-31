# Todo App with React and TypeScript

A Todo application built with React and TypeScript, featuring persistent storage and a clean, responsive UI.

## Features

- Add new todos with a simple form
- Toggle todo completion status
- Delete todos permanently
- Persistent storage (todos stay after page refresh)
- Clean and modern UI
- TypeScript for type safety

## Tech Stack

- React
- TypeScript
- Vite
- Local Storage
- CSS for styling

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/the-mihir/basic-todo-using-react-typeScript.git
cd todo-with-ts
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser to view the app.

## Usage

1. Add a new todo by typing in the input field and pressing Enter or clicking the "Add Task" button
2. Toggle a todo's completion status by clicking the checkbox
3. Delete a todo by clicking the "Delete" button
4. Your todos will persist even after refreshing the page

## Project Structure

```
todo-with-ts/
├── src/
│   ├── components/
│   │   ├── Addtodo.tsx
│   │   ├── Todos.tsx
│   │   └── Footer.tsx
│   ├── store/
│   │   └── todos.tsx
│   ├── App.tsx
│   └── main.tsx
├── public/
├── package.json
└── README.md
```


## Acknowledgments

- React documentation
- TypeScript documentation
- Vite documentation

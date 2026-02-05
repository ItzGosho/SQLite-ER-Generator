# SQLite ER Diagram Generator

A browser-based tool to visualize SQLite database schemas as Entity-Relationship diagrams. Upload your database file and instantly generate interactive ER diagrams.

## Features

- **Drag & Drop Upload** - Simply drag your SQLite database file or click to browse
- **Two Visualization Styles**
  - MySQL Workbench style (custom SVG with draggable tables)
  - Mermaid diagram style
- **Interactive Diagrams** - Drag tables to rearrange, zoom in/out
- **Export Options** - Download as PNG or SVG
- **Privacy First** - All processing happens locally in your browser. Your data never leaves your computer
- **Supports** `.db`, `.sqlite`, `.sqlite3` file formats

## Usage

1. Open `index.html` in a modern web browser
2. Drag and drop your SQLite database file onto the upload area (or click to browse)
3. View your ER diagram with tables, columns, primary keys, and foreign key relationships
4. Switch between MySQL Workbench and Mermaid visualization styles
5. Drag tables to rearrange the layout (MySQL style only)
6. Export your diagram as PNG or SVG

## Technologies Used

- [sql.js](https://github.com/sql-js/sql.js/) - SQLite compiled to WebAssembly
- [Mermaid](https://mermaid.js.org/) - Diagramming library
- [Tailwind CSS](https://tailwindcss.com/) - Styling

## Local Development

No build step required. Simply open `index.html` in your browser or serve it with any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve
```

## License

MIT License

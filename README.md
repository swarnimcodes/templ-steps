# templ-steps

A simple Go web application demonstrating the use of [templ](https://templ.guide/) for type-safe HTML templating with HTMX interactivity.

## Features

- Server-side rendered templates using templ
- Interactive counter with increment/decrement functionality
- Chi router for HTTP routing
- Tailwind CSS for styling
- Static file serving

## Tech Stack

- **Go** - Backend language
- **templ** - Type-safe Go templating
- **Chi** - Lightweight HTTP router
- **Tailwind CSS** - Utility-first CSS framework
- **HTMX** - For dynamic interactions

## Prerequisites

- Go 1.25.4 or higher
- templ CLI (`go install github.com/a-h/templ/cmd/templ@latest`)
- Node.js and npm (for Tailwind CSS)

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/swarnimcodes/templ-steps.git
cd templ-steps
```

2. Install dependencies:
```bash
go mod download
```

3. Generate templ templates:
```bash
templ generate
```

4. Build and run:
```bash
make
# or
go run main.go
```

5. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```
.
├── components/      # Templ templates
├── handlers/        # HTTP handlers
├── static/          # Static assets
├── main.go         # Application entry point
├── Makefile        # Build commands
└── tailwind.config.js
```

## License

MIT

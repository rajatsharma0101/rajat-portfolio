# Rajat Sharma - Portfolio

A responsive portfolio website showcasing DevOps projects and experience.

## Running Locally

### Option 1: Using Docker Compose (Recommended)

```bash
docker-compose up --build
```

Then open your browser to `http://localhost:8080`

### Option 2: Using Docker

```bash
# Build the image
docker build -t rajat-portfolio .

# Run the container
docker run -p 8080:80 rajat-portfolio
```

Then open your browser to `http://localhost:8080`

### Option 3: Using Python HTTP Server

```bash
python3 -m http.server 8000
```

Then open your browser to `http://localhost:8000`

## Project Structure

```
.
├── index.html           # Main HTML file
├── style.css            # Styling
├── script.js            # JavaScript
├── Dockerfile           # Docker configuration
├── docker-compose.yml   # Docker Compose configuration
├── assets/              # Certificates and profile image
└── screenshots/         # Project screenshots
```

## Features

- DevOps Engineer portfolio
- Responsive design
- Project showcase
- Experience timeline
- Skills display
- Contact information

## Docker Images

The Docker setup uses:
- **nginx:alpine** - Lightweight web server for serving static files

## Author

Rajat Sharma - DevOps Engineer
- GitHub: [rajatsharma0101](https://github.com/rajatsharma0101)
- LinkedIn: [rajat-sharma-5a467828b](https://www.linkedin.com/in/rajat-sharma-5a467828b/)
- Email: rajatsharmaa0101@gmail.com

# Docker React

#### Development and Testing Process

- `docker build -t samirprakash/docker-react -f Dockerfile.dev .`
- `docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app samirprakash/docker-react`

#### Production Process

- `docker build -t samirprakash/docker-react .`
- `docker run -p 8080:80 samirprakash/docker-react`

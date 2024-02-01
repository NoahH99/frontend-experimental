# Experimental Frontend for Website

This repository contains the experimental frontend for my website, designed to integrate with multiple microservices. The project serves as a sandbox for exploring and implementing various frontend features and functionalities while interacting with a backend composed of microservices. It is built using modern web technologies, including React, TypeScript, and Vite.

## Building and Running the Project Locally

To build and run the project locally, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/NoahH99/frontend-experimental.git
```

2. Navigate to the project directory:

```bash
cd frontend-experimental
```

3. Install dependencies using npm:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

## Docker

To run the project using Docker, make sure you have Docker installed on your machine. Then, follow these steps:

1. Build the Docker image:

```bash
docker build -t frontend-experimental-local .
```

2. Run a Docker container based on the built image:

```bash
docker run -p 8080:8080 frontend-experimental-local
```

## License

This project is licensed under the [MIT License](https://github.com/NoahH99/frontend-experimental/LICENSE).

```
MIT License

Copyright (c) 2024 Noah Hendrickson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```


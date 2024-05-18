# myapp
This `README.md` provides a complete guide to setting up and running the MyApp project, covering the Go, Next.js, and WordPress components, along with their respective Docker and CI/CD configurations.
# MyApp

MyApp is a web application consisting of three independent components developed using Go, Next.js (TypeScript), and WordPress. This repository contains the source code and Docker configurations for all three components.

## Directory Structure

MyApp/
├── docker-compose.yml
├── go-app/
│ ├── Dockerfile
│ ├── go.mod
│ ├── go.sum
│ └── main.go
###################################################
├── nextjs-app/
│ ├── Dockerfile
│ ├── package.json
│ ├── tsconfig.json
│ └── (other Next.js files)
#######################################
└── wordpress-site/
├── Dockerfile
├── composer.json
├── phpcs.xml
└── wp-content/
└── themes/
└── my-theme/
├── index.php
└── style.css




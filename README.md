# Movie Picture Pipeline

## Project Overview

This project is a containerized Movie application deployed on AWS using Docker, Amazon ECR, Amazon EKS, Kubernetes, and GitHub Actions.

The application consists of:

- **Frontend:** React application
- **Backend:** Python/Flask application
- **Containerization:** Docker
- **Container Registry:** Amazon ECR
- **Orchestration:** Amazon EKS
- **Deployment:** Kubernetes
- **CI/CD:** GitHub Actions
- **Region:** AWS `ap-south-2`

## Application URLs

### Frontend

http://a492e52cef213407c9c18f2dae616c7a-315264914.ap-south-2.elb.amazonaws.com

The frontend application is exposed through an AWS LoadBalancer and can be used by the Udacity reviewer to test the application.

### Backend API

http://a2343445f382a45ecb75a79f6690ae14-172654640.ap-south-2.elb.amazonaws.com/movies

The backend API is exposed through an AWS LoadBalancer.

Example API response:

```json
{
  "movies": [
    {
      "id": "123",
      "title": "Top Gun: Maverick"
    },
    {
      "id": "456",
      "title": "Sonic the Hedgehog"
    },
    {
      "id": "789",
      "title": "A Quiet Place"
    }
  ]
}

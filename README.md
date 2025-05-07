homewell-microservices/
├── README.md
├── services/
│   ├── common/
│   │   ├── config.py
│   │   └── models.py
│   ├── user_service/
│   │   ├── app.py
│   │   ├── models.py
│   │   ├── requirements.txt
│   │   └── Dockerfile
│   ├── booking_service/
│   │   ├── app.py
│   │   ├── models.py
│   │   ├── requirements.txt
│   │   └── Dockerfile
│   └── ... (additional services: provider_service, payment_service, rating_service, notification_service)

# HomeWell Microservices

This repository contains a set of Python 3.12 FastAPI microservices with Pydantic validation built for HomeWell’s post-launch operational support (Post-LOS).

## Services
- **common**: Shared configuration and models
- **user_service**: Manages user onboarding and profile
- **booking_service**: Handles appointment booking and availability
- **provider_service**, **payment_service**, **rating_service**, **notification_service**: follow the same pattern

## Prerequisites
- Python 3.12+
- Docker (optional)

## Running Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-org/homewell-microservices.git
   cd homewell-microservices/services/user_service

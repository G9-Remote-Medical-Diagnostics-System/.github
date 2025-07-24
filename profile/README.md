# G9 Remote Medical Diagnostics System

Welcome to the official GitHub organization for the **G9 Remote Medical Diagnostics System (RMDS)** — a groundbreaking initiative to harness Artificial Intelligence and modern digital technologies to deliver preliminary healthcare diagnostics to communities in rural and underserved regions, starting with Kenya. Our goal is to revolutionize access to early-stage medical support and empower local health ecosystems with scalable, reliable, and intelligent tools.

## About Us

**G9-RMDS** is an innovation-driven project developed by a passionate team of student engineers, AI researchers, system designers, and public health enthusiasts from **Masinde Muliro University of Science and Technology**. This is more than a technical project — it is a social innovation that reflects our deep commitment to improving healthcare equity and inclusion.

We believe that access to diagnostic healthcare should not be limited by geography or infrastructure. With RMDS, we are building a full-stack, AI-powered ecosystem capable of supporting health workers and patients in remote areas using minimal hardware and intermittent connectivity.

This is a project we are proud to develop, as it reflects our dedication to technology with purpose and our responsibility as the next generation of African innovators.

## Project Objectives

- Enable AI-based diagnosis from user-input symptoms and sensor data.
- Support data input from smart health devices (e.g., thermometer, BP monitors).
- Provide patients with guided recommendations: self-care, visit a clinic, or seek emergency attention.
- Link patients with nearby health providers via maps or direct referrals.
- Work seamlessly even in areas with poor or no connectivity using offline-first design.
- Ensure patient data is secure, encrypted, and ethically handled.

## Project Structure

To ensure modularity and scalability, our development is organized into the following repositories:

### [`rmds mobile app`](https://github.com/G9-Remote-Medical-Diagnostics-System/RMDSApp)
The mobile client application (Android/iOS) that allows users to input symptoms, upload optional data (images, temperature, audio), receive AI-based diagnostic feedback, and view nearby health services. Built with offline-first support and optimized for low-spec devices.

### [`rmds web app`](https://github.com/G9-Remote-Medical-Diagnostics-System/RMDSWebsite)
A responsive web interface offering similar diagnostic functionality for use in community health centers or clinics with browser access. Also serves as an admin panel for public health officers.

### [`rmds backend api`](https://github.com/G9-Remote-Medical-Diagnostics-System/RMDSBackend)
The secure API layer that connects mobile/web clients with core backend services, handles user authentication, stores patient diagnostics, manages communication with the AI engine, and integrates external health databases.

### [`rmds ai engine`](https://github.com/G9-Remote-Medical-Diagnostics-System/RMDS_Ai_Engine)
A core module built around machine learning models that analyze symptom and sensor data to suggest probable diagnoses and triage recommendations. Also supports natural language processing for voice/text inputs (future).

### [`rmds iot module`](https://github.com/G9-Remote-Medical-Diagnostics-System/RMDS_Iot_Module)
A Bluetooth and USB-based module that supports integration with smart medical devices such as thermometers, pulse oximeters, and blood pressure monitors, allowing automatic data collection from patients.

### [`rmds admin dashboard`](https://github.com/G9-Remote-Medical-Diagnostics-System/RMDSAdminDashboard)
An administrative interface for doctors, healthcare professionals, and community workers to monitor diagnostics, receive flagged high-risk cases, follow up with patients, and manage referrals.

### [`rmds devops`](https://github.com/G9-Remote-Medical-Diagnostics-System/RMDSDevops)
Infrastructure automation, CI/CD pipelines, monitoring scripts, cloud provisioning, and other tools to ensure stable, secure, and automated deployments for all system components.

### [`rmds docs`](https://github.com/G9-Remote-Medical-Diagnostics-System/RMDSDocs)
Comprehensive documentation for contributors, including system architecture, API references, AI model pipelines, deployment instructions, and compliance guidelines.

## Our Technical Stack

- **Frontend**: React Native, Flutter, HTML5, Tailwind, JavaScript
- **Backend**: Node.js, Express, Firebase, MongoDB, PostgreSQL
- **AI/ML**: Python, TensorFlow, Scikit-learn, FastAPI
- **IoT Integration**: BLE, Arduino, low-cost smart sensors
- **DevOps**: Docker, GitHub Actions, Firebase Hosting, DigitalOcean, Netlify
- **Security**: HTTPS, JWT Auth, OAuth2, AES data encryption

## Key Features

- AI-assisted symptom analysis and probable diagnosis
- Bluetooth health device data collection
- Referral system with real-time clinic locator
- Offline-mode support and local caching
- Role-based access (patients, health workers, doctors)
- Secure and private by design (HIPAA-like compliance model)

## Contribution Guidelines

We welcome contributions from software engineers, data scientists, health workers, medical researchers, and open-source contributors. You can get involved by:

- Forking any repository and submitting pull requests
- Raising or resolving issues
- Contributing data or AI models
- Improving documentation

Please refer to the [`rmds docs`](https://github.com/G9-Remote-Medical-Diagnostics-System/RMDSDocs) repository for technical contribution guidelines and our collaboration roadmap.

## Licensing

All RMDS repositories are open-sourced under the [MIT License](https://choosealicense.com/licenses/mit/) unless otherwise specified. This allows for academic, commercial, and community use with proper attribution.

## Our Vision

We envision a future where intelligent, affordable, and accessible medical tools can assist people in even the most remote corners of the world. We are committed to responsible innovation, ethical data practices, and impactful open-source development.

We invite you to be part of our journey as we continue building a smarter, healthier tomorrow — powered by students, built for humanity.


# Uptime Checker

![스크린샷, 2024-06-25 23-13-54](https://github.com/sioaeko/Uptime-monitor/assets/101755125/3a80f563-ad68-4350-a1f5-dbe353f58088)

Uptime Checker is a simple tool to monitor the availability and SSL certificate status of specified URLs. This project provides a web interface to add URLs for monitoring and an API to check their status.
This version is suitable for typical server deployments
For example, it can be easily deployed in environments such as Ubuntu, Linux Mint, Debian, Kalilinux and Mac



## Features

- **URL Monitoring**: Add URLs to monitor their availability.
- **SSL Certificate Check**: Check the SSL certificate status, including validity and expiration date.
- **Response Time Measurement**: Measure and display the response time of the monitored URLs.

## Setup and Installation

### Prerequisites

- Node.js (v12.x or later)
- npm (v6.x or later)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/sioaeko/Uptime-monitor.git
   cd Uptime-monitor
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

### Running the Project

#### Locally

1. Start the server:

   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:3000`.



## Project Structure

```
Uptime-monitor/
├── public/
│   ├── index.html
│   ├── script.js
│   └── styles.css
├── server.js
├── package.json
└── README.md
```

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License.

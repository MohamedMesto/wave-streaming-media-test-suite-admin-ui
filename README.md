# wave-streaming-media-test-suite-admin-ui
Admin UI extension for the WAVE Streaming Media Test Suite for Devices, providing configuration, test generation, report merging, and export functionalities via a web interface.

### Recommended Repository Structure

wave-streaming-media-test-suite-admin-ui/
├── README.md
├── package.json
├── docker-compose.yml
├── Dockerfile
├── .gitignore
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/           # Views/pages (Dashboard, Reports, Config)
│   ├── services/        # API integration with Test Suite backend
│   ├── hooks/           # Custom React hooks
│   └── App.jsx          # Entry point
├── public/
│   └── index.html
├── tests/               # Unit and integration tests
│   └── e2e/             # End-to-end test scripts
├── docs/
│   ├── setup.md         # Project setup instructions
│   └── design.md        # Conceptual design and integration plan
├── scripts/             # Deployment or automation scripts
└── reports/             # Merged test reports

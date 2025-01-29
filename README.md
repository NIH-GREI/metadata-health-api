# Metadata Health API

API for the demo metadata health reports. Live at [https://metadata-health-api.vercel.app](https://metadata-health-api.vercel.app)

## Setup

1. Install the packages:
```bash
npm install
```

2. Place API data files in the `api/data` directory:
- `providers_attributes.json`
- `providers_stats.json`
- `clients_attributes.json`
- `clients_stats.json`

3. Start the development server:
```bash
npm start
```

The API will then be available at `http://localhost:3000`

## API Documentation

Once running, you can access the API documentation at:
- Swagger UI: `/docs`
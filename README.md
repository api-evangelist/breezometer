# BreezoMeter

BreezoMeter was an environmental intelligence company providing real-time and forecast air quality, pollen counts, wildfire data, and weather information via REST APIs with street-level accuracy. Founded in 2014 in Israel by Ran Korber, Emil Knaisher, and Ziv Lautman, BreezoMeter was acquired by Google in September 2022 for approximately $225 million. Its technology is now integrated into Google Maps Platform.

## APIs

- **Air Quality API** - Real-time and forecast air quality data including AQI scores, pollutant concentrations (CO, NO2, O3, PM10, PM2.5, SO2), and health recommendations
- **Pollen API** - Daily pollen forecasts for up to 5 days covering multiple plant types and pollen indexes
- **Wildfire Tracker+ API** - Real-time wildfire monitoring with area monitoring and precision tracking capabilities
- **Weather API** - Current conditions and hourly/daily forecasts for up to 5 days
- **Environmental Alerts API** - Proactive environmental event notifications via the Insights Engine

## Authentication

All APIs use API key authentication via the `key` query parameter. Keys are obtained through the developer portal at developers.breezometer.com.

**Base URL:** `https://api.breezometer.com/v2/`

## Resources

- [APIs.json Profile](apis.yml)
- [Plans and Pricing](plans/breezometer-plans-pricing.yml)
- [Rate Limits](rate-limits/breezometer-rate-limits.yml)
- [FinOps](finops/breezometer-finops.yml)

## Links

- Website: https://mapsplatform.google.com/maps-products/#environment-section (acquired by Google)
- Documentation: https://docs.breezometer.com/api-documentation/introduction/
- LinkedIn: https://www.linkedin.com/company/breezometer
- X (Twitter): https://x.com/breezometer

## Maintainers

- [Kin Lane](mailto:kin@apievangelist.com)

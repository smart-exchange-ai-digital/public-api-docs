---
layout: home
title: "API Documentation"
permalink: /
---

# Welcome to RiseMedia API Documentation

This documentation provides comprehensive information about the RiseMedia Reporting Service API endpoints for both Supply and Demand partners.

## Quick Navigation

- **[Supply Partner API](api-specification#supply-partner-api)** - Retrieve supply partner reporting data
- **[Demand Partner API](api-specification#demand-partner-api)** - Access demand partner statistics  
- **[Authentication](api-specification#authentication)** - API key requirements and security
- **[Error Handling](api-specification#error-handling)** - Status codes and error responses

## API Overview

The RiseMedia Reporting Service provides REST APIs for retrieving partner reporting data with:

- ✅ **Flexible filtering** - Filter by date ranges, sites, and endpoints
- ✅ **Multiple output formats** - JSON and CSV support
- ✅ **Comprehensive metrics** - Revenue, impressions, requests, and more
- ✅ **Secure authentication** - API key-based access control
- ✅ **Partner isolation** - Supply and demand partners have separate access

## Getting Started

1. **Obtain your API key** from your RiseMedia partner dashboard
2. **Choose your endpoint** - Supply (`/api/v1/supply`) or Demand (`/api/v1/demand`)
3. **Review the documentation** - Check parameters and response formats
4. **Make your first request** - Start with a basic date range query

## API Endpoints

| Endpoint | Purpose | Authentication |
|----------|---------|----------------|
| `GET /api/v1/supply` | Supply partner reporting data | Supply Partner API Key |
| `GET /api/v1/demand` | Demand partner reporting data | Demand Partner API Key |

---

**Need help?** Contact our API support team for assistance with integration and troubleshooting.
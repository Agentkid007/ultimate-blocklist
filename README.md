# Ultimate Pi-hole Blocklist

A comprehensive Pi-hole blocklist specifically curated for South African users, but effective globally. This blocklist focuses on blocking advertising networks, tracking domains, analytics platforms, and malicious sites while maintaining functionality of legitimate services.

## Features

- **Global Ad Networks**: Blocks major advertising platforms like Google Ads, DoubleClick, Facebook Ads, etc.
- **Analytics & Tracking**: Prevents tracking by analytics services, social media platforms, and data collectors
- **South African Focus**: Includes specific domains for local retailers, media platforms, and services
- **Affiliate Trackers**: Blocks referral and affiliate tracking systems
- **Malware Protection**: Basic protection against known malicious domains
- **Regularly Updated**: Maintained and updated to ensure effectiveness

## Installation

### For Pi-hole:
1. Log into your Pi-hole admin interface
2. Go to **Adlists** under **Group Management**
3. Add this URL: `https://raw.githubusercontent.com/Agentkid007/ultimate-blocklist/main/ultimateblocker.txt`
4. Click **Add** and then **Update Gravity**

### For other DNS filtering solutions:
Download the `ultimateblocker.txt` file and import according to your software's documentation.

## What's Blocked

- Advertising networks and ad servers
- Analytics and tracking services  
- Social media tracking pixels
- Affiliate and referral tracking
- South African retail tracking
- Known malware and suspicious domains

## What's NOT Blocked

- Main websites and essential services
- CDNs and content delivery networks
- Legitimate business domains
- Email services and communication platforms

## Contributing

Feel free to suggest additional domains or report false positives by opening an issue.

## License

This blocklist is provided as-is for public use. No warranty or guarantee is provided.
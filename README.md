# ChatWidgets

A Blueprint extension that adds live chat widgets to your Pterodactyl panel with support for multiple providers.

## Supported Providers

- **Crisp Chat** - Modern messaging platform
- **LiveChat.com** - Professional live chat solution
- **Chatwoot** - Open-source customer engagement platform
- **Tawk.to** - Free live chat messaging app
- **Tidio** - AI-powered customer service platform
- **Zendesk Chat** - Enterprise chat solution
- **Zoho SalesIQ** - Sales and support chat platform
- **LiveAgent** - Comprehensive customer service software

## Installation

1. Download the extension
2. Install via Blueprint: `blueprint -install chatwidgets`

## Configuration

1. Go to Admin Panel → Extensions → ChatWidgets
2. Select your preferred chat provider
3. Enter the required Widget Token/ID for your provider
4. For Chatwoot: Also enter your base URL
5. For LiveAgent: Also enter your script URL (e.g., `https://yoursubdomain.ladesk.com/scripts/track.js`)
6. Save settings

The chat widget will now appear on all user dashboard pages.

## Requirements

- Pterodactyl Panel
- Blueprint Framework
- Active account with your chosen chat provider

## Features

- Support for 8 major chat providers
- Easy provider switching via dropdown
- Provider-specific configuration fields
- Direct links to provider dashboards

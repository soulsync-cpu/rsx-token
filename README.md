# RSX Token

A token management and claiming application built with modern web technologies.

## Overview

This project provides a web-based interface for managing and claiming RSX tokens. It includes a service worker for offline functionality and a responsive HTML interface.

## Features

- **Token Claiming**: Simple interface to claim RSX tokens ([claim.html](claim.html))
- **Dashboard**: Main dashboard interface ([index.html](index.html))
- **Offline Support**: Service worker enabled for offline functionality
- **Responsive Design**: Works across different devices and screen sizes

## Project Structure

```
├── index.html          # Main dashboard page
├── claim.html          # Token claiming interface
├── sw.js              # Service worker for offline support
├── assets/            # Static assets and resources
├── LICENSE            # Project license
└── README.md          # This file
```

## Getting Started

1. Open the project in your web browser
2. Navigate to `index.html` for the main dashboard
3. Use `claim.html` to claim tokens
4. The service worker will automatically cache assets for offline use

## Service Worker

The included `sw.js` service worker enables:
- Offline functionality
- Asset caching
- Improved performance

## License

See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

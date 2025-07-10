# MR.OSINT-X

**MR.OSINT-X** is an advanced Open Source Intelligence (OSINT) framework for cybercrime investigation, threat intelligence, digital forensics, and reconnaissance. It integrates hundreds of APIs, AI-powered modules, and open-source tools for comprehensive threat analysis.

## 🚀 Features

- 19+ Specialized OSINT modules (phone, email, crypto, darkweb, social, image, VIN, and more)
- AI-powered risk scoring and behavioral analysis
- Unified CLI, Web UI, and REST API interfaces
- TOR and VPN support for privacy and operational security
- Modular, extensible architecture
- International database and compliance support

## 📦 Project Structure

- `index.html` — Main landing page
- `docs-index.html` — Full documentation and module overview
- `coming-soon.html` — Placeholder for upcoming features/community
- `style.css` — Basic styles (not used by main site, see inline Tailwind)
- `docs-style.css` — Styles for documentation

## 🧩 Modules Overview

- Phone Number OSINT
- Email OSINT
- Domain/IP/Hosting OSINT
- Cryptocurrency & Wallet OSINT
- Darkweb OSINT
- Social Media OSINT
- Image/Face/Visual OSINT
- Satellite OSINT & GEO Tracking
- Vehicle/VIN/License Plate OSINT
- Banking & Financial OSINT
- Company & Business Intelligence
- IP Address Intelligence
- AI Intelligence Layer
- Intelligence Agency & Global Risk OSINT
- Malware & File Intelligence
- Global OSINT Engine
- Advanced Social Media Investigation
- YouTube OSINT
- Indian Document OSINT

See [docs-index.html](docs-index.html) for details.

## 🛠️ Quick Start

### Docker (Recommended)
```sh
git clone https://github.com/mrradix-ad/mr-osint-x
cd mr-osint-x
docker-compose up -d
```

### Manual Installation
```sh
sudo apt update && sudo apt install -y python3-pip python3-venv tor postgresql redis-server
git clone https://github.com/mrradix-ad/mr-osint-x
cd mr-osint-x
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 setup.py init_db
```

## 💡 Usage Examples

- Phone scan:  
  `mr-osint-x --phone +1234567890 --full-scan`
- Email scan:  
  `mr-osint-x --email target@example.com --leaks --social`
- Crypto wallet:  
  `mr-osint-x --wallet 1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa --trace-funds`

See [docs-index.html](docs-index.html) for more.

## 🌐 API Integration

- REST API:  
  `POST /api/v1/phone-intel`  
  `POST /api/v1/image-analysis`  
  `POST /api/v1/ai-assessment`

- Telegram Bot and more: see [docs-index.html](docs-index.html#api)

## 🔒 Security & Compliance

- TOR integration, VPN support, API key rotation, rate limiting
- Data encryption, secure storage, audit trails
- GDPR/CCPA compliance features

## 📖 Documentation

Full documentation and module details: [docs-index.html](docs-index.html)

## 🧑‍💻 Community & Support

- [GitHub Issues](https://github.com/mrradix-ad/mr-osint-x/issues)
- Discord, Telegram, Email: see [docs-index.html](docs-index.html#community)

---

© 2025 MR.OSINT-X Project. Open source under MIT License.  
For research and authorized
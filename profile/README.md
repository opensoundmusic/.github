# Open Sound

Open Sound is an open-source, self-hosted music platform built for users who value privacy, ownership, and control.  
It provides a full ecosystem that allows anyone to host, manage, and play their own music library using modern open technologies.

---

## Overview

Open Sound is designed as a modular system:

| Component | Description | Stack |
|------------|--------------|--------|
| **Core** | The backend server and database layer. Runs on Node.js with PocketBase, fully containerized using Docker and Docker Compose. | Node.js, PocketBase, Docker |
| **App** | The cross-platform client that connects to your self-hosted server. Built with Flutter and optimized for mobile and desktop. | Flutter |
| **YTMusic Plugin** | An optional Node.js extension that fetches metadata from YouTube Music and can download tracks for personal use. | Node.js |

Each part is open source, modular, and can run independently.

---

## Philosophy

Open Sound is built with three main principles:

1. **Self-Hosting by Default** – All data and media stay on the user’s machine.  
2. **Privacy and Control** – No third-party tracking, no remote servers.  
3. **Open Technology** – Built with widely used, open-source tools to ensure transparency and longevity.

---

## Repository Structure

| Repository | Description |
|-------------|--------------|
| [core](https://github.com/opensoundmusic/core) | Backend and database layer |
| [app](https://github.com/opensoundmusic/app) | Flutter client application |
| [ytmusic-plugin](https://github.com/opensoundmusic/ytmusic-plugin) | Optional metadata and download plugin |

---

## Legal Notice

Open Sound and its components do not host, distribute, or stream copyrighted material.  
All media is stored locally by the user.  
Each repository includes its own license and disclaimer outlining legal responsibilities and limitations.

---

## License

All Open Sound repositories are licensed under the MIT License.  
You are free to use, modify, and distribute the code, provided that proper credit is given and the license terms are preserved.

---

## Contributing

Contributions are welcome.  
Please follow the existing structure and respect the project’s focus on legality, privacy, and open standards.  
Bug reports, feature suggestions, and pull requests are encouraged.

---

© 2025 Open Sound Organization. All rights reserved.

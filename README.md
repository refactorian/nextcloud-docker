<p align="center"><img src="https://nextcloud.com/c/uploads/2023/02/logo_nextcloud_white.svg" width="300"></p>

# Nextcloud Docker
- Nextcloud v28.x
- Postgres v16.x

# Requirements
- Stable version of [Docker](https://docs.docker.com/engine/install/)
- Compatible version of [Docker Compose](https://docs.docker.com/compose/install/#install-compose)

# How To Deploy
- `docker compose up -d`

# Notes

### Nextcloud App
- URL: http://localhost

### Docker compose commands
- Build or rebuild services
    - `docker compose build`
- Create and start containers
    - `docker compose up -d`
- Stop and remove containers, networks
    - `docker compose down`
- Stop all services
    - `docker compose stop`
- Restart service containers
    - `docker compose restart`
- Run a command inside a container
    - `docker compose exec [container] [command]`

# What is Nextcloud?

[Nextcloud](https://nextcloud.com/) is a powerful, open-source, and self-hosted collaboration platform that provides file hosting, sharing, communication, and more. It allows individuals and organizations to have control over their data and communication, offering a secure and customizable solution for various use cases.

**Key Features:**

- **File Hosting and Sharing:**
   - Store and share files securely with fine-grained access controls.
   - Collaborative editing for documents, spreadsheets, and presentations.

- **Calendar and Contacts:**
   - Integrated calendar and contacts for efficient personal and team scheduling.
   - CalDAV and CardDAV support for seamless synchronization with various clients.

- **Communication:**
   - Built-in chat and video conferencing for real-time communication.
   - Collaborative editing during video calls for enhanced productivity.

- **Security:**
   - End-to-end encryption for file and communication security.
   - Two-factor authentication (2FA) and other security measures to protect user accounts.

- **Customization:**
   - Extensive theming and customization options to tailor the interface.
   - App ecosystem for additional functionality and integrations.

- **Collaboration and Productivity:**
   - Shared documents and collaborative editing in real-time.
   - Workflow features, such as comments and versioning, for effective teamwork.

- **Access Anywhere:**
   - Web-based interface accessible from any device with a browser.
   - Mobile apps for iOS and Android for on-the-go access.

- **Integration:**
   - Integration with third-party services like LDAP, SSO, and more.
   - API support for developers to extend functionality and integrate with other applications.

- **File Versioning and Recovery:**
   - Version control for files with the ability to restore previous versions.
   - File recovery options in case of accidental deletion or changes.

- **Task Management:**
    - Built-in task management for personal and team productivity.
    - To-do lists and project tracking features.

- **Monitoring and Logging:**
    - Logging and monitoring capabilities for administrators.
    - System insights and analytics for performance optimization.

- **File Sync and Share:**
    - Synchronize files across devices with the desktop and mobile clients.
    - Share files with external users through secure links and permissions.

Nextcloud is an extensible platform that continues to evolve with a strong focus on user privacy and data control. Its diverse set of features makes it suitable for personal use, small businesses, and larger enterprises looking for a self-hosted collaboration solution.
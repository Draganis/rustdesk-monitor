# RustDesk Monitor for Home Assistant

This custom integration lets you monitor the online status of RustDesk clients using your own relay server.

## Features

- Track multiple RustDesk target IDs
- Add/remove clients dynamically via the UI
- Shows online status (binary sensor)
- Generates clickable `rustdesk://` links (sensor)
- Each client becomes a Home Assistant device

## Installation

### 1. Add the Repository to HACS

Go to **HACS > Integrations > Custom Repositories**  
Add:

```
https://github.com/Draganis/rustdesk-monitor
```

Category: **Integration**

### 2. Install via HACS

Search for "RustDesk Monitor" in HACS integrations and install.

### 3. Configure

- Add a server entry with your Source-ID and RustDesk relay settings
- Use the **Options** button to add clients (name + ID)
- Optionally remove them later

## Requirements

- Your RustDesk clients must be routed via a public or local relay server
- No authentication or encryption required (TCP-based)

## Credits

Created by [@Draganis](https://github.com/Draganis)

# App Configuration Files

This repository contains configuration files for various applications and tools I use in my development and home server setup.

## 📁 Structure

### `/cursor/`
Contains Cursor IDE configuration profile:
- **`default.code-profile`** - Complete Cursor IDE profile with settings including:
  - Font configurations (Fira Code with ligatures)
  - Terminal settings (MesloLGS NF font, zsh profile)
  - Editor preferences (line height, font size)
  - Git and debugging configurations
  - Material icon theme

### `/homarr/`
Contains Homarr dashboard configuration:
- **`default.json`** - Complete Homarr homelab dashboard setup featuring:
  - **Media Server Stack**: Plex, Overseerr, Tautulli
  - **Content Management**: Sonarr, Radarr, Readarr, Bazarr
  - **Download Management**: qBittorrent, Prowlarr  
  - **Widgets**: Weather, date/time, download speed monitoring, torrent status
  - **Location**: Configured for Dhaka timezone and weather
  - Custom styling with indigo/green color scheme

### `/raycast/`
Contains Raycast launcher configuration:
- **`Raycast 2025-08-17 11.59.52.rayconfig`** - Raycast settings and extensions backup

## 🚀 Usage

### Cursor Profile
To use the Cursor configuration:
1. Copy `cursor/default.code-profile` to your Cursor profiles directory
2. Import via Cursor Settings → Profiles → Import Profile

### Homarr Dashboard
To use the Homarr configuration:
1. Copy `homarr/default.json` to your Homarr config directory
2. Restart Homarr service
3. Update IP addresses in the config to match your homelab setup

### Raycast Configuration  
To use the Raycast configuration:
1. Import `raycast/Raycast 2025-08-17 11.59.52.rayconfig` via Raycast Settings → Advanced → Import Configuration

## 🔧 Customization

Feel free to modify these configurations for your own setup:
- Update IP addresses and ports in Homarr config
- Adjust font preferences in Cursor profile  
- Modify timezone/location settings for weather widgets

## 📝 Notes

- Homarr config includes API key placeholders - you'll need to configure these with your actual API keys
- The configuration assumes a standard *arr stack setup on local network (192.168.0.176)
- All sensitive information (passwords, API keys) are stored as placeholders

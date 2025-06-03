# System Requirements

## User Roles
- **Admin**: Uploads ads, defines target locations
- **Viewer**: Simulated endpoint for seeing what gets shown

## Core Use Cases
1. Admin uploads an ad (image, language, sponsor, target country)
2. Admin registers a sports match (teams, location, date)
3. Viewer opens match simulation — the system uses their location to determine which ad is shown

## Core Entities
- Advertisement (id, image_url, language, target_location)
- Match (id, teams, location, datetime)
- Viewer (location, screen type: stadium/TV)

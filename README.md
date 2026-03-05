# Smart Campus Navigator

A real-time digital guide for seamless indoor and outdoor campus navigation.

## 📖 Description

Smart Campus Navigator is an interactive application designed to help students, faculty, and visitors find their way around sprawling institutional campuses.

### The Problem
Large campuses with multiple departments, labs, and administrative blocks are often a maze for newcomers. Physical signboards can be outdated, and general-purpose maps (like Google Maps) often lack precise indoor details.

### The Solution
This project provides:

- **Turn-by-Turn Navigation**: Step-by-step guidance from your current location to any room or facility.
- **Indoor Mapping**: Detailed floor plans for complex buildings (labs, libraries, and offices).
- **Real-Time Updates**: Notifications for event locations, temporary blockages, or room changes.

## 🛠️ Technology Stack

- **Frontend**: React Native (Mobile) / React.js (Web)
- **Backend**: Node.js with Express
- **Database**: PostgreSQL (with PostGIS for spatial data)
- **Mapping**: Leaflet.js / Mapbox API
- **Algorithms**: Dijkstra's or A* Algorithm for shortest path calculation

## 🚀 Installation Steps

### Clone the Repository:
```bash
git clone https://github.com/potluritejpavan-coder/smart-campus-navigator.git
cd smart-campus-navigator
```

### Install Frontend Dependencies:
```bash
cd client
npm install
```

### Setup Backend:
```bash
cd ../server
npm install
```

### Configure Environment:
Create a `.env` file in the server directory and add:
```
MAPBOX_API_KEY=your_mapbox_api_key
DATABASE_URL=your_postgresql_database_url
```

### Run Locally:
```bash
# From the root directory
npm start
```

## 💻 Usage Examples

- **Find a Classroom**: Type "Lab 402" in the search bar to see the fastest walking route.
- **Event Routing**: Click on the "Annual Fest" banner to get directions directly to the main auditorium.
- **Accessibility Mode**: Toggle the "Elevator Only" switch to find routes suitable for wheelchairs.

## 🗺️ Project Status & Roadmap

**Status**: 🏗️ In Development

- [x] Basic outdoor map integration
- [ ] Indoor floor-plan rendering
- [ ] Voice-assisted navigation
- [ ] Augmented Reality (AR) markers for building entrances

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Tejpavan Potluri** (@potluritejpavan-coder)

## 🙏 Acknowledgements

- Campus planning teams for providing building layouts
- Open-source mapping community
- Contributors and testers
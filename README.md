# zMove

<p align="center">
  <img src="assets/logo.png" alt="kolibdev logo" width="200"/>
</p>

A Zalo Data file management and organization tool built with Go and Wails.

### Prerequisites
- Go 1.23 or higher
- Node.js and npm
- Wails CLI

### Installation

1. Install Wails CLI:
```bash
go install github.com/wailsapp/wails/v2/cmd/wails@latest
```

2. Clone the repository:
```bash
git clone https://github.com/KoLibDev/zMove.git
cd zMove
```

3. Install frontend dependencies:
```bash
cd ui/frontend
npm install
```

### Development

To run the application in development mode:
```bash
cd ui
wails dev
```

### Building
To build the application:
```bash
cd ui
wails build
```

The executable will be created in `ui/build/bin` directory.


# Real-Time Signal Viewer

A Python-based application for real-time visualization and analysis of signal data with multiple viewing and control capabilities.

## Features

- Multi-channel signal visualization
- Real-time signal monitoring 
- Dual graph display with linking capability
- Playback controls (Play, Pause, Rewind)
- Signal manipulation tools:
  - Channel selection
  - Color customization
  - View range control
  - Zoom functionality
  - Channel hiding/showing
- Non-rectangular plotting option
- Report generation with snapshots
- Channel gluing functionality

## Demo Video

https://github.com/yourusername/signal-viewer/blob/main/Data/task1.mp4

## Dependencies

- Python 3.x
- PyQt6
- PyQtGraph
- ReportLab
- NumPy

## Project Structure

```
signal-viewer/
│
├── src/
│   ├── main.py           # Application entry point
│   ├── ui_main.py        # Main window UI implementation
│   ├── graph_widget.py   # Custom graph widget implementation
│   └── utils.py          # Utility functions
│
└── resources/
    └── styles/           # CSS styling files
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/signal-viewer.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
python src/main.py
```

2. Load signal data using File > Open
3. Use playback controls to navigate through signals
4. Adjust visualization settings using the control panel

## Screenshots

[Screenshots would be added here]

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to branch
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.


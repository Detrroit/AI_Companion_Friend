# AI Companion Friend

An AI-powered virtual companion with voice interaction and Live2D avatar. This project is based on Open-LLM-VTuber, providing a personalized AI friend experience.

## Features

- 🗣️ **Voice Interaction**: Real-time voice conversation capabilities
- 😊 **Live2D Avatar**: Animated character with expressive emotions
- 👁️ **Visual Perception**: Can see and respond to visual input
- 🔒 **Privacy Focused**: Runs locally on your machine
- 🖥️ **Cross-platform**: Works on Windows, macOS, and Linux

## Getting Started

### Prerequisites

- Python 3.10 or higher
- Git (for cloning and updates)
- [uv](https://github.com/astral-sh/uv) (for dependency management)

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Detrroit/AI_Companion_Friend.git
   cd AI_Companion_Friend
   ```

2. Install dependencies:
   ```bash
   uv sync
   ```

3. Configure your AI companion by editing `conf.yaml`

4. Run the server:
   ```bash
   uv run run_server.py
   ```

5. Access the web interface at `http://localhost:12393/`

## Configuration

The main configuration file is `conf.yaml`. You can customize:

- Character personality and behavior
- Voice settings (TTS/ASR models)
- Live2D model selection
- LLM provider and settings

See `config_templates/` for example configurations.

## Usage

1. Open your browser and navigate to `http://localhost:12393/`
2. Allow microphone access when prompted
3. Start talking to your AI companion!
4. Click and drag to move the character around your screen
5. Customize the character's appearance and behavior through configuration

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Uses Live2D Cubism for character animation
- Various open-source LLM, TTS, and ASR models

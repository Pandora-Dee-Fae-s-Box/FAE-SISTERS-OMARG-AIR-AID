# ARCHON: AI Remote Holistic Controller

A local-tool bridge for NLP models. This is the base README; domain-specific editions live in `README-V2.md` through `README-V7.md`.

## Introduction

Welcome to ARCHON - the AI Remote Holistic Controller. ARCHON serves as a versatile bridge, connecting local or remote NLP models with RCON (Remote Console), API systems, and local tool runtimes, transforming them into a powerful, holistic control mechanism for various applications. It's designed to empower users with a highly configurable platform, integrating local NLP, API endpoints, and RCON instructions.

### Key Features

- **Model Integration**: Seamlessly connects with a compatible local or hosted NLP model.
- **API & RCON Connectivity**: Offers on-the-fly API instruction generation and RCON management.
- **Advanced Web Browsing**: Enhances the model's web browsing or tool-call capabilities, simulating an advanced OS-level web browser.
- **Customizable Training Data**: Users can define their training datasets, stored either locally or on a GitHub fork.
- **Entware Module & Custom Firmware**: Available as an Entware module or can be integrated into custom router firmware for advanced users.
- **Comprehensive Documentation**: Follows the terms and conditions of the -OMARG-AIR-AID project on darkilluminatus GitHub.

## Installation

### Prerequisites

- Python 3.
- Access to a compatible local or hosted model endpoint (e.g., Ollama, vLMM, OpenAI-compatible API)
- Basic understanding of API endpoints and RCON protocol

### Step-by-Step Guide

1. **Clone the Repository**: 
   ```
   git clone https://github.com/darkilluminatus/-OMARG-AIR-AID.git
   ```
2. **Navigate to ARCHON Directory**: 
   ```
   cd -OMARG-AIR-AID/models/ARCHON/
   ```
3. **Install Dependencies**: 
   ```
   pip install -r requirements.txt
   ```
4. **Configure Your Model**: Follow the included instructions to set up your model endpoint and system prompt.

## Configuration

Edit `config.json` to customize ARCHON for your specific needs. This includes setting up:

- API endpoints
- RCON server details
- Local training data sources
- model parameters

## Usage

1. **Start ARCHON**: 
   ```
   python archon.py
   ```
2. **Connect to Your Model**: Ensure your model is running and accessible.
3. **Configure API/RCON Instructions**: Use the provided templates to create custom instructions.
4. **Advanced Browsing**: Utilize ARCHON's browsing capabilities for enhanced information retrieval.

## Customization

- **Training Data**: Customize your model by specifying your training datasets.
- **Integrate into Custom Firmware**: For advanced users, detailed instructions are provided for firmware integration.

## Support

For support, please refer to the [GitHub Issues](https://github.com/darkkilluminatus/-OMARG-AIR-AID/issues) page of the -OMARG-AIR-AID project.

## License

ARCHON is released under the same terms and conditions as the -OMARG-AIR-AID project. For more details, see the LICENSE file in the repository.

---

By using ARCHON, you are agreeing to abide by the terms and conditions of the -OMARG-AIR-AID project. Enjoy the power and flexibility it brings to your models and connected systems!

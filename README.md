# repuMonta

## Description
A business inventory automation solution using n8n on Docker. This project streamlines inventory management processes through workflow automation.

## Prerequisites
- Docker
- Docker Compose
- At least 2GB of RAM available
- 2GB of free disk space

## Installation

1. Clone this repository:
```bash
git clone https://github.com/marko0925/repuMonta.git
cd repuMonta
```

2. Start the application:
```bash
docker-compose up -d
```

The n8n interface will be available at `http://localhost:5678`

## Configuration
The application runs on port 5678 by default. You can modify the configuration in the `docker-compose.yml` file.

## Data Persistence
All workflows and credentials are stored in a Docker volume named `n8n_data`.

## Usage
1. Access the n8n interface at `http://localhost:5678`
2. Log in with your credentials
3. Start creating your inventory automation workflows

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details

## Support
For support, please open an issue in the GitHub repository or contact the maintainers.

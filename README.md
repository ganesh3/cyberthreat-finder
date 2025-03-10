# CyberThreat PathFinder: Agentic Graph Intelligence System

## Overview

CyberThreat PathFinder is an innovative graph-based intelligence system that helps security teams visualize attack paths and prioritize defenses against sophisticated adversaries. By leveraging GPU-accelerated graph analytics, our solution transforms complex threat data into actionable security intelligence.

![CyberThreat PathFinder Dashboard](https://github.com/user/cyberthreat-pathfinder/raw/main/images/dashboard.png)

## Key Features

- **Natural Language Interface**: Query complex threat data using everyday language
- **GPU-Accelerated Analytics**: Leverages NVIDIA cuGraph for high-performance path finding and centrality measures
- **Attack Path Visualization**: Discover and visualize potential attack paths from threat actors to critical assets
- **Threat Actor Profiling**: Analyze techniques and capabilities of specific threat actors
- **Risk-Based Prioritization**: Multi-factor scoring incorporating vulnerability, asset and threat data
- **Privacy-Preserving Analysis**: Fully local operation with on-device LLM - no API keys required

## Architecture

CyberThreat PathFinder integrates several powerful technologies:

1. **ArangoDB**: Graph database for storing cybersecurity relationships
2. **NetworkX & cuGraph**: Graph analytics with GPU acceleration
3. **Local LLM (Mistral)**: Natural language understanding and agentic workflow
4. **MITRE ATT&CK**: Framework for mapping threat actor techniques
5. **Interactive Visualizations**: Dynamic threat representation using Matplotlib

## Getting Started

### Prerequisites

- Python 3.8+
- CUDA-capable NVIDIA GPU (optional, for acceleration)
- Google Colab environment (for notebook execution)

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/user/cyberthreat-pathfinder.git
   cd cyberthreat-pathfinder
   ```

2. Open the notebook in Google Colab or run locally

### Usage

1. Run the notebook to set up the environment and initialize the graph database
2. Use the interactive interface to query the threat intelligence system
3. Analyze results through visualizations and recommendations

## Example Queries

- "What are the most critical vulnerabilities in our infrastructure?"
- "Analyze the risk to our Database Server"
- "Show me potential attack paths from APT28 to our Domain Controller"
- "What techniques are commonly used by APT28?"

## Future Development

- Integration with real-time threat intelligence feeds
- Temporal analysis to track threat evolution over time
- Integration with SIEM and SOAR platforms
- Advanced countermeasure simulation and "what-if" analysis

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the Apache License - see the LICENSE file for details.

## Acknowledgements

- [MITRE ATT&CK](https://attack.mitre.org/) for threat actor techniques framework
- [CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) for vulnerability data
- [Ollama](https://ollama.ai/) for local LLM implementation

---

*CyberThreat PathFinder: Turning complex threat data into actionable security intelligence with graph analysis that helps teams visualize attack paths and prioritize defenses against advanced threats.*

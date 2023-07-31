
# Input preparation for Synthetic Population for Agent-based Simulation for Greater Cairo Region

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains several Jupyter notebooks to prepare different components of a synthetic population of Greater Cairo for agent-based simulations. It was created in collaboration with the Data Team of Transport for Cairo. 

## Notebooks

- Preparing a building database from OSM addresses, buildings, and Google Open Buildings
- Creating a statistically representative synthetic population based on census and surveys
- Randomly assigning individuals to address points to match today's spatial distribution
- Generating and assigning activity profiles to individuals based on origin-destination and travel interviews
- Creating and assigning travel profiles for an average weekday
- Generating the number and types of different activities (work, leisure, education) and assigning them to address points
- Rescaling populations based on 2030 populations to match predefined changes in population density and constellation

The resulting data acts as input to an existing pipeline for synthetic population generation and activity-based MATSIM mobility simulations: https://github.com/eqasim-org/ile-de-france/tree/cairo
In this process, the locations are matched with individuals depending on activity chains and distances.

## Data

The process relies on different data sources referenced throughout and can be downloaded for free or requested. If any data is missing, do not hesitate to reach out.

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgments

This project was developed as part of the Anthropolis Chair's (IRT SystemX/CentraleSupélec) research on sustainable urban mobility. We would like to acknowledge the support and contributions of the research team and funding agencies. Furthermore, it was initiated during a fellowship at Transport for Cairo and benefitted from a research visit at the American University in Cairo.

## Contact

For questions or inquiries, please contact:

Tjark Gall
Email: tjark.gall@urban-framework.com

# BlueLeaks Data Analysis Project

## Introduction

This project aims to analyze the BlueLeaks data, a significant data breach involving approximately 270 GB of information from over 200 U.S. police departments. The data spans from August 1996 to June 2020 and includes emails, videos, images, URLs, links to web pages, Social Security Numbers (SSN), and personal documents of police officers and suspects.

## Project Overview

The BlueLeaks data provides an unfiltered view into the operations and communications within U.S. law enforcement agencies. This project explores various aspects of the dataset, focusing on the patterns and incidents documented. Key areas of analysis include:

- Incident counts by state
- Categories of crimes (theft, fraud, property damage, arrests)
- Patterns over time
- Privacy and ethical considerations

## Data Preparation

To ensure accurate and meaningful analysis, significant data cleaning and preparation were undertaken. Key steps included:

- **State Standardization**: Ensuring all state entries conform to ISO 3166-2 codes.
- **Removing Null Values**: Eliminating rows with null values in critical columns.
- **Data Anonymization**: Redacting sensitive information, such as SSNs, to protect privacy.

## Key Findings

- **Incident Counts by State**: Missouri had the highest incident count, representing over 87% of the data.
- **Crime Categories**: Crimes were grouped into four main categories: theft, fraud, property damage, and arrests.
- **Temporal Patterns**: Analysis of crime patterns from 2010 to 2020 revealed significant spikes in fraud and property damage in specific years.

## Ethical Considerations

The BlueLeaks dataset contains sensitive information. While the analysis provided valuable insights, ethical considerations regarding data privacy and anonymization were paramount. No personally identifiable information (PII) is shared in this project.

## Project Structure

- **Data**: Contains the cleaned and prepared datasets.
- **Scripts**: Python scripts used for data cleaning, analysis, and visualization.
- **Reports**: Findings and visualizations generated from the analysis.
- **README.md**: This file, providing an overview of the project.

## References

- Rasmussen, 2020: [What’s inside of BlueLeaks?](https://iowastatedaily.com/235764/opinion/rasmussen-whats-inside-of-blueleaks/)
- Dallas Morning News, 2020: [Did you hear about the giant computer hack of 200 US police departments? It’s called BlueLeaks.](https://www.dallasnews.com/news/watchdog/2020/07/23/did-you-hear-about-the-giant-computer-hack-of-200-us-police-departments-its-called-blueleaks/)
- Krebs, 2020: Detailed information about the Netsential breach.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes.

## Contact

For questions or suggestions, please open an issue or contact me directly at natanaelefreires@gmail.com.

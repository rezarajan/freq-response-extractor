# Frequency Response Extractor
This tool is provided as a quick way to extract frequency response data from rtings, for use in tools like [AutoEQ](https://squig.link/).

### Folder Structure
| Data Type | Location |
| --------- | -------- |
| Config Data | `data/configs/headphone_name/config.yaml`|
| Frequency Response Data | `data/configs/headphone_name/freq.csv` |

### Usage
The script is provided as a Jupyter Notebook. Ensure that the following libraries are installed, then update the notebook variables to point to the relevant outputs, and run:
- Numpy
- Pandas
- YAML

### Examples
A sample config and output is provided in the data folder, for the Logitech G333 headphones.
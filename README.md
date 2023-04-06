# Laser Welding Data Visualization

This project visualizes the relationship between energy input, area, flux density, and extent for laser welding processes. It generates an interactive scatter plot using Plotly, allowing users to explore the data and view images of the corresponding welding results on hover.

## Features

- Interactive scatter plot of energy input vs. area
- Color scale representing the extent
- Display of welding parameters (power and speed) and welding images on hover
- Export of the plot to an HTML file

## Installation

To set up the project, follow these steps:

1. Clone the repository.

2. Navigate to the project directory:
cd CNN_model/preprocessing.ipynb


3. Create a virtual environment:
python3 -m venv venv

4. Activate the virtual environment:
- On Windows:
  ```
  venv\Scripts\activate
  ```
- On macOS and Linux:
  ```
  source venv/bin/activate
  ```

5. Install the required packages:
pip install -r requirements.txt


## Usage

1. Make sure the virtual environment is activated.
2. Run the `preprocessing.ipynb` script to generate the scatter plot:
3. View the generated scatter plot in the `flux_density_vs_area.html` file.

## Dependencies

- Python 3.7 or later
- Plotly
- NumPy
- pandas
- Pillow

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

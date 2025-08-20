# CUDS Aerofoil Competition 2025

## Overview

Brief available [here](./aerofoil%20comp.pdf).

The CAD models were made in Autodesk Fusion 360, available at [`0 deg.iges`](./models/0%20deg.iges) and [`15 deg.step`](./models/15%20deg.step) (only worked with these specific formats), using the [E71 airfoil profile](http://airfoiltools.com/airfoil/details?airfoil=e71-il) ([`e71.dat`](./models/e71.dat)) with my custom winglet.

They're available on Onshape [here](https://cad.onshape.com/documents/eeabfa041e1ab182c924ed06/w/96821fddbd5169d921f82ecc/e/38bc785b00623b1c6c418b1c).

CFD was run using Simscale, with the project [here](https://www.simscale.com/projects/kingwaffleiii/aerospace_competition/).
CSV data was exported from Simscale and is available in [`0 deg.csv`](./results/0%20deg.csv) and [`15 deg.csv`](./results/15%20deg.csv).

Results were parsed with [`parse_csv.ipynb`](./parse_csv.ipynb), which uses Pandas and Plotly to visualise the data and then exported as PDFs: [`0 deg.pdf`](./results/0%20deg.pdf) and [`15 deg.pdf`](./results/15%20deg.pdf).

## Renders

### 0 degrees AoA

![0 deg model 1](./models/0%20deg-1.png)
![0 deg model 2](./models/0%20deg-2.png)

### 15 degrees AoA

![15 deg model 1](./models/15%20deg-1.png)
![15 deg model 2](./models/15%20deg-2.png)

## Results

### 0 degrees AoA

**Lift/drag ratio: `14.264`**

### 15 degrees AoA

**Lift/drag ratio: `5.155`**

## Graphics

### 0 degrees AoA

#### Lift and Drag Coefficients Over Time

![Lift and Drag Coefficients Over Time](./graphics/0%20deg-1.png)

#### Cutting Plane

![Cutting Plane](./graphics/0%20deg-2.png)

#### Particle Traces

![Particle Traces 1](./graphics/0%20deg-3.png)

![Particle Traces 2](./graphics/0%20deg-4.png)

### 15 degrees AoA

#### Lift and Drag Coefficients Over Time

![Lift and Drag Coefficients Over Time](./graphics/15%20deg-1.png)

#### Cutting Plane

![Cutting Plane](./graphics/15%20deg-2.png)

#### Particle Traces

![Particle Traces 1](./graphics/15%20deg-3.png)

![Particle Traces 2](./graphics/15%20deg-4.png)

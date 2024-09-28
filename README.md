# Monte_Carlo
# Monte Carlo Method for Numerical Integration

This Python project implements the **Monte Carlo method** for numerical integration, using random sampling to estimate the area under a curve for any given function (in this example, `e^x` is used, but the function can be changed easily).

## Key Features:
- Uses **random sampling** to estimate the area under a curve.
- Demonstrates two approaches:
  1. The **Marble approach**, where random points are generated and counted based on their position relative to the curve.
  2. The **Mean approach**, which calculates the average value of the function and multiplies it by the range.
- Visualizes the **Monte Carlo simulation**, showing points that fall above and below the curve.

## How It Works:
1. **Random points** are generated within a user-defined range (`x` values from `-1 to 2` in this example).
2. Points are categorized based on whether they fall **above** or **below** the curve (e.g., `e^x`).
3. Two estimates of the area are computed:
   - Using the **Marble approach**, which counts points below the curve.
   - Using the **Mean approach**, which averages the function’s values across sampled points.
4. The results are visualized with two plots:
   - A **Marble approach** graph showing sampled points relative to the curve.
   - A **Mean approach** graph visualizing the average function values.

## Usage:
Run the Python script to execute the Monte Carlo simulation and view the results.

```bash
python monte_carlo_integration.py


# O3_deposition_schemes
A Python package for calculating ozone deposition and conductance using a range of published stomatal and non-stomatal deposition schemes. The package also contains a canopy-scale photosynthesis scheme.

## Features

- Stomatal conductance parameterisations
- Non-stomatal deposition to soil and leaf cuticles
- Aerodynamic and quasi-laminar boundary-layer resistance calculations
- Canopy scaling and integration
- Sunlit and shaded leaf calculations 
- Workflows 

## Installation

### Install from GitHub

```bash
pip install git+https://github.com/flossie-brown/O3_deposition_schemes.git
```

### Install locally for development

Clone the repository and install it in editable mode:


```bash
git clone https://github.com/flossie-brown/O3_deposition_schemes.git
cd O3_deposition_schemes
python -m pip install -e ".[dev]"
```


## Quick start

```python
import ozone_deposition as od

# Replace with a function and inputs that are implemented in this package.
# result = od.example(...)
```


## Implemented schemes

| Scheme | Component | DOI |
|---|---|---|
| Jarvis | Stomatal conductance | 10.1046/j.1365-3040.1999.00407.x |
| Ball–Berry | Stomatal conductance | 10.1007/978-94-017-0519-6_48|
| Medlyn | Stomatal conductance | 10.1111/j.1365-2486.2010.02375.x |
| Zhang | Non-stomatal deposition | 10.1016/S1352-2310(02)00567-8 |
| Zhou | Non-stomatal deposition | 10.5194/acp-17-1361-2017|
| Clifton | Non-stomatal deposition | 10.1029/2020JD032398|
| Clifon | Non-stomatal deposition | 10.1029/2021JG006362|


## Units and conventions

--


## Documentation

--



## Citation

If you use this package in your work, please cite it. Citation metadata is provided in [`CITATION.cff`](CITATION.cff).


## Contributing

Bug reports, suggestions, and contributions are welcome.


## License

This project is released under the license specified in LICENSE.

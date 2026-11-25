# Calcium Silicate Calculator
A standalone browser-based material mass balance and oxide molar ratio calculator. Open `index.html` locally; no installation or network required.

Inputs: wet mass, solids, CaO, SiO2, Al2O3, LOI, fiber and user-defined effective fractions. Outputs: dry mass, water, dry fractions, total and effective elemental molar ratios, LOI and fiber mass.

## Manual verification
For 56.077 kg pure CaO and 60.084 kg pure SiO2 at 100% solids, Ca/Si should equal 1.000. Set effective Si to 50% and effective Ca to 100%; effective Ca/Si should equal 2.000. Zero Si yields N/A. Negative inputs must be rejected.

Examples are synthetic. Effective fractions are assumptions, not measured reaction rates. This is an engineering calculation aid, not a validated production control system.

## License
MIT is proposed; the repository owner must confirm rights and add the license before public release.

# Regulators

## Installation
Run in the terminal:

```ato install regulators``

Add to your ato project:

LDO
```import LDOReg3V3 from "regulators/regulators.ato```
Buck
```import BuckReg3V3 from "regulators/regulators.ato```
Boost
```import BoostReg5V from "regulators/regulators.ato```

## Overview

This package includes a variety of regulators that can be used to power your project, including:

### LDO
Low-dropout regulators are a simple way to step down voltage. They are easy to use and are available in a variety of packages. They are not very efficient, but are a good choice for low-power applications.
### Buck
Buck converters are a more efficient way to step down voltage. They are more complicated to use, but are a good choice for high-power applications.
### Boost
Boost converters are a good way to step up voltage.


## Features
### LDO
- **Input Voltage** 2.5V - 13.2V
- **Configurable Output Voltage** 1.2V - 12V
- **Output Current** 200mA
- **Low Quiescent Current** 55uA, 1uA in shutdown

### Buck
- **Input Voltage** 4.5V - 42V
- **Output Voltage** Configurable
- **Output Current** 600mA
[Data sheet](https://www.ti.com/lit/ds/symlink/lm2842-q1.pdf?ts=1702689166245&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FLM2842-Q1)

### Boost
- **Input Voltage** 0.9V - 4.75V
- **Output Voltage** 2.5V - 5V
- **Output Current** 3A
[Data sheet](https://www.diodes.com/assets/Datasheets/PAM2401.pdf)

## Contributing

We welcome contributions and suggestions to improve this module. Please submit your contributions as pull requests on our GitHub repository.

## License

This package documentation is provided under the [MIT License](#).

## Contact

For further inquiries or support, please contact us at [email@example.com](mailto:email@example.com).

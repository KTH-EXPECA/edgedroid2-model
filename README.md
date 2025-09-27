# EdgeDroid 2

EdgeDroid 2 is a model for human emulation in Wearable Cognitive Assistance.

For more context on the design and usage of this library see our publication ["Emulating Reactive Workloads for Cyber-Human Systems: A Data-Driven Methodology"](https://doi.org/10.1109/ACCESS.2025.3614639).

If you use this library in your work/research, please cite us:
```bibtex
@ARTICLE{11180943,
  author={Muñoz, Manuel Olguín and Klatzky, Roberta and Satyanarayanan, Mahadev and Gross, James},
  journal={IEEE Access}, 
  title={Emulating Reactive Workloads for Cyber-Human Systems: A Data-Driven Methodology}, 
  year={2025},
  keywords={Behavioral sciences;Real-time systems;Videos;Load modeling;Correlation;Benchmark testing;Delays;Computational modeling;Biomedical monitoring;Adaptation models;Distributed Systems;Modeling and Prediction;Virtual and Augmented Reality;Wearable Computers},
  doi={10.1109/ACCESS.2025.3614639}}

```

## Usage

You can import this library into your project by including it as a git dependency.
For instance, in your `requirements.txt`:

```txt title=requirements.txt
-e git+https://github.com/KTH-EXPECA/edgedroid2-model.git@master#egg=edgedroid
```

## Development

Prerequisites: examples and tests require the `cmake` binary to be installed.
Additionally, the `gabriel-lego` library, also used for tests and examples, only works under Python 3.10.

To develop on this library, clone this repository, then install it as an editable Python module. Make sure to enable the `dev` optional dependencies:

```bash
git clone https://github.com/KTH-EXPECA/edgedroid2-model.git
cd edgedroid2-model
pip install -Ue '.[dev]'
```

## License

This work is made available through an Apache v2.0 license.
See the [LICENSE](LICENSE) file for details.

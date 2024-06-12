# PyBeMoBIL

**PyBeMoBIL** is a Python-based reimplementation of the BeMoBIL pipeline, originally coded in MATLAB. This library provides a comprehensive suite of tools for processing and analyzing mobile brain/body imaging (MoBI) data. Designed to be user-friendly and efficient, PyBeMoBIL leverages the power and flexibility of Python to offer enhanced performance and ease of use.

## Features

- **Complete Reimplementation**: All functionalities of the original BeMoBIL pipeline are now available in Python.
- **User-Friendly**: Simplified interfaces and extensive documentation to help users get started quickly.
- **High Performance**: Optimized for speed and efficiency, making it suitable for large datasets.
- **Extensible**: Easily extendable with additional modules and custom scripts.
- **Open Source**: Fully open-source, encouraging community contributions and collaboration.

## Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.7 or higher
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/PyBeMoBIL.git
    cd PyBeMoBIL
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Usage

To use PyBeMoBIL, follow these steps:

1. Import the library in your Python script:
    ```python
    import pybemobil as pbm
    ```

2. Load your MoBI data:
    ```python
    data = pbm.load_data('path/to/your/data')
    ```

3. Process the data using the provided functions:
    ```python
    processed_data = pbm.process_data(data)
    ```

4. Analyze the processed data:
    ```python
    results = pbm.analyze_data(processed_data)
    ```

For detailed usage instructions, refer to the [user manual](#).

## Contributing

We welcome contributions from the community! If you have ideas for new features, bug fixes, or improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

Please check out our [contributing guidelines](#) and [code of conduct](#) for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Original BeMoBIL pipeline developers
- Contributors to the PyBeMoBIL project

## Contact

If you have any questions or feedback, feel free to open an issue or contact us at sina.esmaeili@umontreal.ca.

---

Thank you for using PyBeMoBIL! We hope it helps you in your research and projects.

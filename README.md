# biosiac: KMer Level Tokenizer for DNA & Protein Sequences 🧬

![GitHub release](https://img.shields.io/badge/Release-Download%20Latest%20Version-blue)

Welcome to the **biosiac** repository! This project focuses on developing a KMer level tokenizer specifically designed for DNA and protein sequences. Tokenization is a crucial step in bioinformatics, enabling efficient processing and analysis of biological data. 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The **biosiac** tokenizer utilizes KMer encoding to transform biological sequences into a format suitable for machine learning and other analytical methods. KMer encoding breaks down sequences into smaller, manageable parts, making it easier to analyze patterns and structures within DNA and protein sequences. This project aims to enhance the understanding of biological data through effective tokenization.

## Features

- **KMer Tokenization**: Efficiently tokenize DNA and protein sequences into KMer representations.
- **Flexible Encoding**: Support for different KMer sizes to cater to various analysis needs.
- **Bioinformatics Integration**: Seamlessly integrate with existing bioinformatics tools and frameworks.
- **User-Friendly Interface**: Simple command-line interface for ease of use.
- **Documentation**: Comprehensive documentation to guide users through installation and usage.

## Installation

To install **biosiac**, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/PrayagParmar77/biosiac.git
   ```

2. Navigate to the project directory:
   ```bash
   cd biosiac
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the latest release from [here](https://github.com/PrayagParmar77/biosiac/releases) and execute the required files.

## Usage

Using **biosiac** is straightforward. After installation, you can start tokenizing sequences. Here’s how to use the tokenizer:

1. Prepare your DNA or protein sequences in a text file, with each sequence on a new line.

2. Run the tokenizer:
   ```bash
   python tokenizer.py -i input_sequences.txt -k 3 -o output_tokens.txt
   ```

   In this command:
   - `-i` specifies the input file.
   - `-k` sets the KMer size (e.g., 3 for trimer).
   - `-o` specifies the output file for the tokens.

3. Check the output file for the tokenized sequences.

For more detailed usage instructions, refer to the documentation included in the repository.

## Examples

Here are some examples to illustrate how **biosiac** works:

### Example 1: Tokenizing DNA Sequences

Suppose you have the following DNA sequences:

```
ATCGATCG
GTCAGTCA
```

Running the tokenizer with KMer size 2 will produce:

```bash
python tokenizer.py -i dna_sequences.txt -k 2 -o dna_tokens.txt
```

The output file will contain:

```
AT
TC
CG
GA
AT
TC
GT
TC
CA
```

### Example 2: Tokenizing Protein Sequences

For protein sequences, the process is similar. Given the following sequences:

```
MKTIIALSYIFCLVF
```

Using the tokenizer with KMer size 4:

```bash
python tokenizer.py -i protein_sequences.txt -k 4 -o protein_tokens.txt
```

The output will show:

```
MKTII
KTIIA
TIIAL
IIALS
IALSY
ALSYI
LSYIF
SYIFC
YIFCL
IFCLV
FCLVF
```

## Contributing

We welcome contributions to **biosiac**! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch to your fork.
5. Open a pull request to the main repository.

Please ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out via GitHub issues or contact me directly at [your_email@example.com](mailto:your_email@example.com).

For the latest releases, visit [here](https://github.com/PrayagParmar77/biosiac/releases) to download and execute the required files.

Thank you for checking out **biosiac**! We hope you find it useful for your bioinformatics projects.
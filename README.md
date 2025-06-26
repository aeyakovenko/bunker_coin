# Bunker Consensussy: A Low Bandwidth, Shortwave Radio-Compatible Blockchain Protocol with Alternative Consensus Mechanisms

This repository contains the LaTeX source for the BunkerCoin whitepaper: "A Low Bandwidth, Shortwave Radio-Compatible Blockchain Protocol" by Anatoly Yakovenko.

## Prerequisites

You need a working LaTeX distribution installed. The document has been tested with:

- **TeX Live 2023** (recommended)
- **MiKTeX** (latest stable)

### Required Packages

The document uses the following LaTeX packages:
- `inputenc` - UTF-8 input encoding
- `fontenc` - T1 font encoding for better text rendering
- `amsmath` - Enhanced math typesetting
- `amssymb` - Additional mathematical symbols
- `geometry` - Page layout customization
- `hyperref` - PDF metadata and hyperlinks

These packages are included in most standard LaTeX distributions.

## Compilation Instructions

### Method 1: Using pdfLaTeX (Recommended)
```bash
pdflatex bunker_coin.tex
pdflatex bunker_coin.tex  # Run twice for proper cross-references
```

### Method 2: Using XeLaTeX
```bash
xelatex bunker_coin.tex
xelatex bunker_coin.tex  # Run twice for proper cross-references
```

### Method 3: Using LuaLaTeX
```bash
lualatex bunker_coin.tex
lualatex bunker_coin.tex  # Run twice for proper cross-references
```

### One-line Compilation
For a clean compilation with automatic cleanup:
```bash
pdflatex bunker_coin.tex && pdflatex bunker_coin.tex
```

## Output

The compilation will generate:
- `bunker_coin.pdf` - The final whitepaper document
- `bunker_coin.aux` - Auxiliary file for cross-references
- `bunker_coin.log` - Compilation log
- `bunker_coin.out` - Hyperref outline information

## Document Features

- **Professional formatting** with proper margins and typography
- **UTF-8 encoding** for international character support
- **T1 font encoding** for better PDF text rendering
- **Hyperlinked PDF** with proper metadata
- **Mathematical notation** support for cryptographic formulas
- **Cross-platform compatibility** across multiple LaTeX engines

## Troubleshooting

### Common Issues

1. **Missing packages**: Install the full TeX Live distribution or missing packages individually
2. **Font issues**: Ensure T1 font encoding is available
3. **Compilation warnings**: Run pdflatex twice to resolve cross-references

### System-specific Installation

**Ubuntu/Debian:**
```bash
sudo apt install texlive-latex-base texlive-latex-recommended texlive-latex-extra texlive-fonts-recommended
```

**macOS (with MacTeX):**
```bash
brew install --cask mactex
```

**Windows (MiKTeX):**
Download and install from [miktex.org](https://miktex.org/)

## Technical Specifications

- **Document Class**: `article`
- **Input Encoding**: UTF-8
- **Font Encoding**: T1
- **Engines Supported**: pdfLaTeX, XeLaTeX, LuaLaTeX
- **Output Format**: PDF/A compatible

## Contributing

When editing the LaTeX source:

1. Maintain UTF-8 encoding
2. Test compilation with multiple engines
3. Run the document through a LaTeX linter if available
4. Ensure proper mathematical notation formatting
5. Verify PDF metadata is correctly set

## License

This document describes the BunkerCoin protocol design and is intended for academic and research purposes.

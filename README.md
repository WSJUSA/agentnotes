# Agent Notes

A personal space for exploring the world of building AI agents, with a focus on DSPy tutorials and insights.

## About

This is a Quarto-based website that serves as a knowledge repository for AI agent development, particularly focused on DSPy (Declarative Self-improving Language Programs). The site contains tutorials, tips, and insights gathered from the AI development community.

## Features

- **DSPy Tutorials**: Comprehensive guides for various DSPy optimizers
  - CORPO Optimizer with LangWatch integration
  - MIPROv2 Optimizer for reliable AI
  - SIMBA Optimizer (placeholder)
  - BootstrapFewShot Optimizer (placeholder)
  - LabeledFewShot Optimizer (placeholder)
- **Modern Web Design**: Clean, responsive layout with Bootstrap styling
- **Code Highlighting**: Syntax highlighting for Python and JSON
- **Search Functionality**: Built-in search for easy navigation

## Getting Started

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) installed on your system
- Python 3.12+ (for DSPy tutorials)
- Git

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd agentnotes
```

2. Install Python dependencies (if running DSPy tutorials):
```bash
pip install -r requirements.txt
```

3. Build the site locally:
```bash
quarto preview
```

The site will be available at `http://localhost:4848`

### Development

- **Content**: Add new tutorials as `.qmd` files in the root directory
- **Styling**: Modify `_quarto.yml` for site configuration
- **Assets**: Place images in `assets/images/`

## Project Structure

```
agentnotes/
├── _quarto.yml          # Quarto configuration
├── index.qmd            # Homepage
├── assets/
│   └── images/          # Site images and logos
├── _site/               # Built site (generated)
├── *.qmd                # Tutorial content files
└── *.ipynb              # Jupyter notebooks
```

## Tutorials

### Available Tutorials

1. **CORPO Tutorial** (`copro_tutorial.qmd`)
   - Complete guide to DSPy's CORPO optimizer
   - LangWatch integration for observation
   - Grammar classification example

2. **MIPROv2 Tutorial** (`2025-07-09-miprov2-tutorial.qmd`)
   - Step-by-step guide to MIPROv2 optimizer
   - Customer support ticket classification
   - Performance visualization with LangWatch

3. **Introduction** (`2025-07-09-welcome-to-jekyll.qmd`)
   - Basic DSPy concepts and setup

### Placeholder Tutorials

- SIMBA Optimizer
- BootstrapFewShot Optimizer  
- LabeledFewShot Optimizer

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `quarto preview`
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- **Author**: Will James
- **Social**: [LinkedIn] [X Platform]

## Acknowledgments

- DSPy team for the excellent framework
- LangWatch for observation and visualization tools
- The AI development community for shared insights and tips 
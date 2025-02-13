# Pritchett Analyzer

A Python script implementing Lant Pritchett's four-part "smell tests" of development importance. Analyzes World Bank indicators against criteria for development relevance.

See:
- https://www.cgdev.org/blog/your-impact-evaluation-asking-questions-matter-four-part-smell-test
- https://paulromer.net/urbanization-passes-the-pritchett-test/

## Quick Start

```bash
# Clone the repository
git clone https://github.com/kennethtiong/pritchett-analyzer.git
cd pritchett-analyzer
```

```bash
# Install dependencies
uv venv
source .venv/bin/activate
uv pip install pandas numpy requests click matplotlib
```

```bash
# Run the analysis
python pritchett-analyzer.py run-analysis

# With options
python pritchett-analyzer.py run-analysis --exclude-singapore --outdir ~/analysis --n-threads 8
```

## License

MIT License - see LICENSE file

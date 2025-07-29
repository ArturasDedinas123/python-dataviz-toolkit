# Contributing to Python DataViz Toolkit

Thank you for your interest in contributing to the Python DataViz Toolkit! This document provides guidelines and information for contributors.

## 🤝 How to Contribute

### Types of Contributions

1. **New Plot Recipes** - Add new visualization types to the plot-recipes collection
2. **Cheat Sheet Updates** - Improve or expand the library cheat sheets
3. **Bug Fixes** - Fix errors in existing code or documentation
4. **Documentation** - Improve README files, add examples, or clarify instructions
5. **Performance Improvements** - Optimize existing code for better performance

### Getting Started

1. **Fork the Repository**
   ```bash
   git clone https://github.com/yourusername/python-dataviz-toolkit.git
   cd python-dataviz-toolkit
   ```

2. **Set Up Development Environment**
   ```bash
   pip install -r requirements.txt
   jupyter notebook
   ```

3. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📊 Adding New Plot Recipes

### Naming Convention
Follow the established pattern: `##_plot_type_name.ipynb`
- Use two-digit numbers (01, 02, etc.)
- Use lowercase with underscores
- Be descriptive but concise

### Notebook Structure
Each plot recipe notebook should include:

#### 1. Title and Description
```markdown
# Plot Type Name
Brief description of when and why to use this plot type.

## 📊 Use Cases
- Use case 1
- Use case 2
- Use case 3

## 📚 Libraries Used
- Library 1 (version)
- Library 2 (version)
```

#### 2. Imports and Setup
```python
# Standard imports
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objects as go

# Set random seed for reproducibility
np.random.seed(42)

# Configure matplotlib
plt.style.use('default')
plt.rcParams['figure.figsize'] = (10, 6)
plt.rcParams['font.size'] = 12
```

#### 3. Sample Data Generation
```python
# Generate reproducible sample data
# Include comments explaining the data structure
def generate_sample_data():
    """Generate sample data for demonstration."""
    # Your data generation code here
    return data

data = generate_sample_data()
```

#### 4. Multiple Examples
Include at least 3 variations:
- Basic example
- Customized styling
- Advanced/interactive version

#### 5. Best Practices Section
```markdown
## 💡 Best Practices
- When to use this plot type
- Performance considerations
- Accessibility tips
- Common pitfalls to avoid
```

### Code Quality Standards

1. **Reproducible Examples**
   - Set random seeds
   - Include all necessary imports
   - Use relative paths for any data files

2. **Clear Documentation**
   - Comment complex code sections
   - Explain parameter choices
   - Include output descriptions

3. **Consistent Styling**
   - Use the established color palette
   - Follow consistent figure sizing
   - Apply uniform font settings

4. **Error Handling**
   - Include basic error checking
   - Provide fallback options
   - Handle common edge cases

## 🗂️ Updating Cheat Sheets

### Structure Guidelines

1. **Organized Sections**
   - Basic syntax
   - Common parameters
   - Styling options
   - Advanced features
   - Tips and tricks

2. **Code Examples**
   - Keep examples concise
   - Include expected output
   - Show both simple and complex usage

3. **Cross-References**
   - Link to related plot recipes
   - Reference official documentation
   - Point to additional resources

## 🔍 Code Review Process

### Before Submitting

1. **Test All Code**
   - Run all cells in your notebooks
   - Verify outputs are correct
   - Check for any error messages

2. **Check Documentation**
   - Spell check all text
   - Verify all links work
   - Ensure formatting is consistent

3. **Validate Structure**
   - Follow naming conventions
   - Include required sections
   - Update index files if needed

### Pull Request Guidelines

1. **Descriptive Title**
   - Summarize the change clearly
   - Use conventional commit format if applicable

2. **Detailed Description**
   - Explain what was added/changed
   - Include screenshots for visual changes
   - Reference any related issues

3. **Testing Information**
   - Describe how you tested the changes
   - Include system information if relevant
   - Note any dependencies added

## 🐛 Reporting Issues

### Bug Reports
Include:
- **Environment**: Python version, OS, library versions
- **Steps to Reproduce**: Detailed steps to trigger the bug
- **Expected Behavior**: What should happen
- **Actual Behavior**: What actually happens
- **Code Sample**: Minimal example demonstrating the issue

### Feature Requests
Include:
- **Use Case**: Why is this feature needed?
- **Proposed Solution**: How should it work?
- **Alternatives**: Other approaches considered
- **Examples**: Similar features in other libraries

## 📝 Style Guidelines

### Python Code
- Follow PEP 8 style guidelines
- Use meaningful variable names
- Include docstrings for functions
- Maximum line length: 88 characters (Black formatter standard)

### Markdown Documentation
- Use proper heading hierarchy
- Include emoji for visual organization
- Keep paragraphs concise
- Use code blocks for examples

### Jupyter Notebooks
- Clear cell organization
- Descriptive markdown cells
- Consistent output formatting
- Remove unnecessary outputs before committing

## 🏆 Recognition

Contributors will be:
- Listed in the project README
- Credited in individual notebooks they create
- Acknowledged in release notes
- Invited to join the maintainer team for significant contributions

## 📞 Getting Help

- **Questions**: Open a GitHub issue with the "question" label
- **Discussions**: Use GitHub Discussions for broader topics
- **Direct Contact**: Email project maintainers for sensitive issues

## 📄 License

By contributing, you agree that your contributions will be licensed under the same MIT License that covers the project.

---

Thank you for helping make Python data visualization more accessible to everyone! 🎨📊

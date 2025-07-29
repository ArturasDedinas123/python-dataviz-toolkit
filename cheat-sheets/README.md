# 🗂️ Data Visualization Cheat Sheets

Quick reference guides for Python's most popular data visualization libraries. Each notebook contains essential syntax, common parameters, and practical examples to speed up your coding workflow.

## 📚 Available Cheat Sheets

| Library | File | Description | Best For |
|---------|------|-------------|----------|
| **Overview** | [`overview.ipynb`](./overview.ipynb) | Library comparison and selection guide | Choosing the right tool |
| **Matplotlib** | [`matplotlib.ipynb`](./matplotlib.ipynb) | Core plotting library fundamentals | Fine-grained control, publication plots |
| **Seaborn** | [`seaborn.ipynb`](./seaborn.ipynb) | Statistical data visualization | Quick statistical plots, beautiful defaults |
| **Plotly** | [`plotly.ipynb`](./plotly.ipynb) | Interactive web-ready visualizations | Interactive dashboards, web apps |
| **Pandas** | [`pandas.ipynb`](./pandas.ipynb) | Built-in DataFrame plotting | Quick exploratory analysis |

## 🎯 How to Use These Cheat Sheets

### Quick Reference Workflow:
1. **Start with Overview** - Understand which library fits your needs
2. **Pick Your Library** - Open the specific cheat sheet
3. **Find Your Syntax** - Use the organized sections to locate what you need
4. **Copy & Adapt** - Use the code snippets in your projects

### Each Cheat Sheet Contains:

#### 📖 **Syntax Reference**
- Essential import statements
- Basic plotting commands
- Common parameters and options
- Keyboard shortcuts and tips

#### 🎨 **Styling Guide**
- Color schemes and palettes
- Font and text customization
- Layout and spacing options
- Theme and style presets

#### 🔧 **Configuration Tips**
- Performance optimization
- Output formats and saving
- Integration with Jupyter
- Common troubleshooting

#### 💡 **Best Practices**
- When to use each library
- Performance considerations
- Accessibility guidelines
- Professional presentation tips

## 🚀 Quick Start Examples

### Matplotlib Essentials:
```python
import matplotlib.pyplot as plt
plt.figure(figsize=(10, 6))
plt.plot(data)
plt.title("My Plot")
plt.show()
```

### Seaborn Statistical Plots:
```python
import seaborn as sns
sns.scatterplot(data=df, x="var1", y="var2", hue="category")
plt.show()
```

### Plotly Interactive:
```python
import plotly.express as px
fig = px.scatter(df, x="var1", y="var2", color="category")
fig.show()
```

## 📊 When to Use Each Library

| Scenario | Recommended Library | Why |
|----------|-------------------|-----|
| **Quick Data Exploration** | Pandas plotting | Built into DataFrame, minimal code |
| **Statistical Analysis** | Seaborn | Statistical plots, beautiful defaults |
| **Publication Quality** | Matplotlib | Fine control, publication standards |
| **Interactive Dashboards** | Plotly | Web-ready, highly interactive |
| **Complex Multi-panel** | Matplotlib + Seaborn | Maximum flexibility |

## 🛠️ Setup Requirements

All cheat sheets work with the standard data science stack:

```bash
pip install numpy pandas matplotlib seaborn plotly jupyter
```

Or use the requirements from the plot-recipes directory:
```bash
pip install -r ../plot-recipes/requirements.txt
```

## 💡 Pro Tips

### Workflow Optimization:
- **Bookmark frequently used patterns** - Keep common snippets handy
- **Combine libraries** - Use multiple libraries in the same project
- **Start simple** - Begin with defaults, then customize
- **Use templates** - Create reusable plotting functions

### Performance Tips:
- **Choose the right tool** - Matplotlib for static, Plotly for interactive
- **Optimize data size** - Sample large datasets for exploration
- **Cache results** - Save plots to avoid re-computation
- **Use vectorized operations** - Leverage NumPy and Pandas efficiency

## 🔗 Related Resources

- **[Plot Recipes](../plot-recipes/)** - Complete working examples for specific plot types
- **[Matplotlib Gallery](https://matplotlib.org/stable/gallery/)** - Official example gallery
- **[Seaborn Gallery](https://seaborn.pydata.org/examples/)** - Statistical plot examples
- **[Plotly Documentation](https://plotly.com/python/)** - Interactive plot reference

## 🤝 Contributing

To improve these cheat sheets:

1. **Add missing syntax** - Common patterns you use frequently
2. **Update examples** - Keep code current with latest library versions  
3. **Improve organization** - Better categorization and searchability
4. **Add tips** - Performance hints and best practices
5. **Fix errors** - Correct any outdated or incorrect information

## 📝 Usage Guidelines

These cheat sheets are designed for:
- ✅ **Quick reference** during coding sessions
- ✅ **Learning** new library features
- ✅ **Teaching** visualization concepts
- ✅ **Standardizing** team coding practices

---

💡 **Tip:** Keep these cheat sheets open in separate tabs while working on data visualization projects for quick reference!

📈 Happy plotting! 🎨

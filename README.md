# 📊 Geoscience-Geostats

> **Practical Geostatistics Tips, Workflows & Code for Earth Scientists**  
> *From Variograms to Kriging — Applied to Wells, Seismic, and Subsurface Modeling*

🔗 **LinkedIn**: [Ali Mahdy](https://www.linkedin.com/in/ali-mahdy-9484a037) | 🎥 **YouTube**: [@Dralimahdy](https://www.youtube.com/@Dralimahdy)  
📍 Post-PhD Researcher & Lecturer in Geophysics | Ain Shams University, Cairo, Egypt  

---

## 📌 About This Repository

**Geoscience-Geostats** is a curated, open-source collection of geostatistical methods, practical tips, and reproducible Python workflows designed specifically for geoscientists, reservoir engineers, petrophysicists, and Earth science researchers.

Whether you're analyzing spatial continuity in well logs, building porosity models with kriging, simulating facies distributions, or quantifying uncertainty in subsurface properties — this repository helps you apply geostatistics *correctly*, *efficiently*, and *geologically*.

💡 **Every tip is paired with a detailed LinkedIn post** featuring visuals, real-data examples, and community discussion:  
👉 Follow for weekly geostatistics insights: [linkedin.com/in/ali-mahdy-9484a037](https://www.linkedin.com/in/ali-mahdy-9484a037)

---

## 🎯 What You'll Find Here

### 🔹 Geostatistics Fundamentals for Geoscience
| Tip | Focus | Geoscience Application |
|-----|-------|----------------------|
| `01_stationarity.md` | Understanding stationarity assumptions | Well-log interpolation, reservoir property modeling |
| `02_variogram_basics.md` | Experimental vs. theoretical variograms | Spatial continuity analysis of porosity/permeability |
| `03_variogram_models.md` | Spherical, exponential, Gaussian — when to use which | Modeling anisotropy in fluvial vs. carbonate systems |
| `04_search_neighborhood.md` | Defining search radius & direction for kriging | Honoring geological trends in property estimation |

### 🔹 Interpolation & Simulation Methods
| Tip | Focus | Geoscience Application |
|-----|-------|----------------------|
| `05_kriging_types.md` | Ordinary, simple, universal, co-kriging | Integrating seismic attributes as secondary data |
| `06_conditional_simulation.md` | SGS, SIS for uncertainty quantification | Generating equiprobable reservoir realizations |
| `07_indicator_kriging.md` | Categorical variable modeling | Facies probability mapping from sparse well control |
| `08_block_kriging.md` | Upscaling point data to grid cells | Preparing well-log data for reservoir simulation grids |


### 🔹 Common Pitfalls & How to Avoid Them
- 🚫 Ignoring anisotropy in directional variograms → **Always check azimuthal continuity in depositional systems**
- 🚫 Overfitting variogram models to noisy data → **Use cross-validation & geological reasoning**
- 🚫 Using kriging for extrapolation beyond data support → **Remember: kriging is an interpolator, not a predictor**
- 🚫 Treating simulation realizations as deterministic → **Always quantify uncertainty via ensemble statistics**

---

## 🚀 Quick Start

### 1. Browse by Category
```
geoscience-geostats/
├── fundamentals/          # Stationarity, variograms, spatial correlation
├── interpolation/         # Kriging variants, search strategies, validation
├── simulation/           # Sequential Gaussian/Indicator simulation, uncertainty
├── workflows/            # End-to-end pipelines: well logs → property models
├── snippets/             # Copy-paste code for gstools, pykrige, scikit-gstat
├── case_studies/         # Real examples: Gulf of Suez, Mediterranean, Cooper Basin
└── resources/            # Papers, textbooks, datasets, software comparisons
```

### 2. Learn → Apply → Discuss
1. Open a tip file (e.g., `interpolation/05_kriging_types.md`)
2. Run the accompanying Jupyter Notebook with sample data
3. Visit my [LinkedIn](https://www.linkedin.com/in/ali-mahdy-9484a037) for the companion post with visualizations, interpretation tips, and community Q&A
4. Share your results or ask questions — let's learn together!

### 3. Contribute or Request a Tip
- 🐛 Found an error or ambiguity? → [Open an issue](https://github.com/AliMahdy/Geoscience-Geostats/issues)
- 💡 Have a geostatistics tip to share? → Fork → Add your `.md` or `.ipynb` → Submit a [Pull Request](https://github.com/AliMahdy/Geoscience-Geostats/pulls)
- 🎯 Want a tip on a specific topic? → Request it on [LinkedIn](https://www.linkedin.com/in/ali-mahdy-9484a037) or [GitHub Discussions](https://github.com/AliMahdy/Geoscience-Geostats/discussions)

---

## 📚 Learning Path Suggestion

```
🟢 START HERE
   └─ fundamentals/00_geostats_workflow_geoscience.md 
      → The 6-step geostatistical workflow adapted for subsurface problems

🟡 BUILD CORE SKILLS
   ├─ fundamentals/ → Variogram modeling, stationarity, anisotropy
   └─ interpolation/ → Kriging types, validation, geological constraints

🔴 ADVANCE & APPLY
   ├─ simulation/    → Uncertainty quantification, facies modeling
   ├─ workflows/     → Well-to-grid upscaling, seismic integration
   └─ case_studies/  → Real-field applications with open data
```

---

## 🤝 Contributing & Community

| Action | How To |
|--------|--------|
| 🐛 Report a bug or suggest improvement | [Open a GitHub Issue](https://github.com/AliMahdy/Geoscience-Geostats/issues) |
| 💡 Share your geostatistics tip or workflow | Fork → Add content → Submit a [Pull Request](https://github.com/AliMahdy/Geoscience-Geostats/pulls) |
| 💬 Discuss methods or request topics | Comment on [LinkedIn](https://www.linkedin.com/in/ali-mahdy-9484a037) or start a [GitHub Discussion](https://github.com/AliMahdy/Geoscience-Geostats/discussions) |

> 📋 *All contributions should follow the [Code of Conduct](CODE_OF_CONDUCT.md) and include clear explanations, reproducible code, and geological context.*

---

## 📄 License & Citation

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

### 🔖 Cite This Resource
If you use these workflows, tips, or code in your research, teaching, or industry projects, please cite:

```bibtex
@misc{mahdy2026geosciencegeostats,
  author = {Mahdy, Ali},
  title = {Geoscience-Geostats: Practical Geostatistical Workflows for Earth Scientists},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/AliMahdy/Geoscience-Geostats}},
  note = {Companion insights and discussions on LinkedIn: linkedin.com/in/ali-mahdy-9484a037}
}
```

---

## 🌐 Connect with Dr. Ali Mahdy

| Platform | Link |
|----------|------|
| 💼 **LinkedIn** | [Ali Mahdy](https://www.linkedin.com/in/ali-mahdy-9484a037) |
| 🎥 **YouTube** | [@Dralimahdy](https://www.youtube.com/@Dralimahdy) |
| 🐙 **GitHub** | [AliMahdy](https://github.com/AliMahdy) |
| 🌍 **Location** | Cairo, Egypt |

### 🔬 Research & Teaching Focus
```
✓ Rock Physics & Fracture Characterization
✓ Seismic Interpretation & Quantitative Analysis
✓ CCUS (CO₂ Storage) Feasibility & Environmental Risk Assessment
✓ Geothermal Resource Evaluation
✓ Geostatistical Modeling & Uncertainty Quantification in Subsurface Systems
```

---  

*⭐ Star this repo to get notified when new tips and workflows drop!*

> 🙏 Help me grow this open resource:
> 
>• Star ⭐ the repo to support open geoscience education
> 
>• Tag a colleague working on reservoir modeling or spatial analysis
> 
>• Comment below: What's your biggest geostatistics challenge right now?

---

> ⚠️ **Disclaimer**: These materials are for educational and research purposes. Geostatistical modeling involves significant assumptions and uncertainties. Always validate results against geological concepts, laboratory data, well control, and industry QC protocols before applying to commercial, regulatory, or high-stakes subsurface decisions.

---

<p align="center">
  <i>Built with 📊 and 🌍 by Dr. Ali Mahdy</i><br>
  <sub>Empowering geoscientists to model subsurface uncertainty with geological integrity and statistical rigor</sub>
</p>


- Write a LinkedIn content calendar to promote this repo over 4 weeks

Happy modeling, Dr. Ali! 📊🌍🐍

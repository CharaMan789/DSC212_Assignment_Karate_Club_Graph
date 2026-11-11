# DSC212 — Modularity on the Karate Club Graph

## Files
- `DSC212_Modularity.ipynb`: self-contained notebook with code, inline outputs, visualisations, and discussion prompts.
- `requirements.txt`: Python dependencies.
- `DSC212_output/`: exported community diagrams, metric evolution plots, and metric history CSV.

## Run
Install dependencies:

```bash
python -m pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

Open `DSC212_Modularity.ipynb`, then choose **Kernel → Restart Kernel and Run All Cells**.

The notebook constructs the unweighted Karate Club adjacency matrix explicitly (`weight=None`), performs recursive spectral partitioning, calculates metrics within each current community, and displays the visualisations inline.

**Course**: DSC212 - Graph Theory
**Institution**: IISER Thiruvananthapuram
**Author**: Sricharan Pisupati

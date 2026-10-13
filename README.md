# Hanwoo backfat ML benchmark

Analysis code for benchmarking 14 regression models for backfat thickness in Hanwoo cattle under nested cross-validation.

## Requirements

Python 3.13

```
pip install -r requirements.txt
```

## Data

Data are archived on Zenodo: [10.5281/zenodo.23333204](https://doi.org/10.5281/zenodo.23333204) (CC BY 4.0)

Download the following files into `data/`:

- `data/hanwoo_backfat_analysis_dataset.csv`
- `data/hanwoo_backfat_animal_screening.csv`

## Run

```
jupyter lab hanwoo_backfat_benchmark.ipynb
```

Run all cells. `SEED = 27`. Set `FAST = True` in section 01 for a reduced run.

## License

MIT

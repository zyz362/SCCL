# SCCL: Smoothness-Constrained Contrastive Learning for Heliostat Calibration

A dataset and method for heliostat tracking error calibration based on smoothness constraints and contrastive learning.

## Overview

This repository provides a dataset of heliostat tracking errors collected from the Jülich Solar Tower (PSA), Germany. The data supports research on solar concentrator calibration, tracking error prediction, and machine learning-based fault diagnosis.

## Dataset

The file `data/priint_with_ba42.csv` contains **955 records** from **5 heliostats** (AB26, AB52, AD53, AN47, BA42), collected between **January 2022** and **June 2024**.

### Data Fields

| Field | Description |
|-------|-------------|
| `heliostat_id` | Unique heliostat identifier |
| `timestamp` | ISO 8601 measurement timestamp |
| `sample_id` | Unique sample identifier |
| `sun_elevation` | Sun elevation angle (degrees) |
| `sun_azimuth` | Sun azimuth angle (degrees) |
| `axis_1_motor_position` | Motor position for axis 1 |
| `axis_2_motor_position` | Motor position for axis 2 |
| `target_name` | Target: `solar_tower_juelich_lower` or `solar_tower_juelich_upper` |
| `heliostat_lat/lon/alt` | Heliostat geographic coordinates |
| `focal_spot_lat/lon/alt` | Focal spot geographic coordinates |
| `target_center_lat/lon/alt` | Target center geographic coordinates |
| `tracking_error_lat/lon/alt` | Tracking error in each direction |

## Applications

- Heliostat tracking error analysis and calibration
- Smoothness-constrained regression modeling
- Contrastive learning for solar concentrator systems
- Predictive maintenance and fault detection
- Time series analysis of tracking performance

## Citation

If you use this dataset, please cite:

```bibtex
[Citation to be added upon publication]
```

## License

Please refer to the repository for license information.

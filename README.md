# Tracked Vehicle Driving Data

This repository provides tracked-vehicle driving data for energy-management simulation and validation.

## Data Description

The dataset contains six driving cycles of a tracked vehicle. Each cycle is stored as a MATLAB `.mat` file and includes two variables:

- `speed_vector`: vehicle speed profile
- `Yaw_rate`: yaw-rate profile

The files are organized as follows:

| File | Variables |
|---|---|
| `Tracked_vehicle_driving_cycle1.mat` | `speed_vector`, `Yaw_rate` |
| `Tracked_vehicle_driving_cycle2.mat` | `speed_vector`, `Yaw_rate` |
| `Tracked_vehicle_driving_cycle3.mat` | `speed_vector`, `Yaw_rate` |
| `Tracked_vehicle_driving_cycle4.mat` | `speed_vector`, `Yaw_rate` |
| `Tracked_vehicle_driving_cycle5.mat` | `speed_vector`, `Yaw_rate` |
| `Tracked_vehicle_driving_cycle6.mat` | `speed_vector`, `Yaw_rate` |

## Usage

The data can be loaded in MATLAB as follows:

```matlab
data = load('Tracked_vehicle_driving_cycle1.mat');
speed = data.speed_vector;
yaw_rate = data.Yaw_rate;

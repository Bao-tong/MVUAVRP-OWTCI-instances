# MVUAVRP-OWTCI Instances

This repository contains 90 benchmark instances for the multi-vessel and UAV routing problem for offshore wind turbine collaborative inspection.

The dataset is generated from the locations of the Hornsea 1 offshore wind farm and is divided into small-, medium-, and large-scale instance sets.

## Repository structure

```text
MVUAVRP-OWTCI-instances/
│
├── Location/
│   └── Contains the complete Hornsea 1 location dataset, including the depot
│       and the geographical coordinates of all 174 offshore wind turbines.
│
├── Small-scale instances/
│   └── Contains 30 benchmark instances with 10–50 wind turbines and
│       1–3 vessels. Each vessel carries either two or three UAVs.
│
├── Medium-scale instances/
│   └── Contains 30 benchmark instances with 51–100 wind turbines and
│       2–4 vessels. Each vessel carries either two or three UAVs.
│
└── Large-scale instances/
    └── Contains 30 benchmark instances with 101–174 wind turbines and
        3–6 vessels. Each vessel carries either two or three UAVs.

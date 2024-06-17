# Battery Qualification Bench GUI
Battery qualification is a crucial step when building a CubeSat. The team must purchase a batch of cells and evaluate them to ensure they pass the NR-SRD-139 requirement. The GUI serves as a pilot and controls several [Battery Cell Qualification Benches](https://github.com/scsd-cdh/battery_test_firmware). It also logs all the data so that it can be looked at later on.

## Getting Started
To run the application in the development environment the developer must run the following commands.

```bash
yarn install
yarn tauri dev
```

This should launch the application.

## Contribution
Before attempting to contribute to the project, the reader must familiarize themselves with the [Software Design Document](docs/sdd.md). The document explains in detail the architecture of the application and serves as a guide for the development of the tool.


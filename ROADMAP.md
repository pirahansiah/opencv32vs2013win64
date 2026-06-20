# OpenCV 3.2 — Development Roadmap

## 12-Month Vision

Archive the OpenCV 3.2 VS2013 distribution as a historical reference while providing comprehensive migration documentation and toolchain upgrade guidance for enterprise environments.

### Q1: Documentation & Migration
- Create detailed migration guide from VS2013 → VS2022 with OpenCV version mapping
- Document Windows XP end-of-life implications for CV deployments
- Add automated build verification for VS2013 (where still available)
- Create side-by-side code comparison (3.2 vs 4.x vs 5.x)
- Update README with clear EOL timeline and successor pointers

### Q2: Enterprise Support
- Create compatibility matrix for enterprise deployment scenarios
- Document long-term support options for legacy systems
- Add Docker-based build environment for VS2013 (where feasible)
- Create performance baseline benchmarks for legacy hardware
- Add CI pipeline for regression testing on Windows 7/10

### Q3: Migration Tooling
- Build automated code migration tool (3.2 → 4.x API translation)
- Create OpenVINO migration examples for Intel-optimized inference
- Document ONNX Runtime as DNN module replacement
- Add TensorRT migration guide for NVIDIA GPU targets
- Create hardware recommendation guide for enterprise upgrades

### Q4: Archive & Sunset
- Mark repository as archived with clear successor links
- Create final release with all documentation consolidated
- Write "VS2013 Era" retrospective for enterprise CV development
- Ensure all tutorial links remain accessible
- Add permanent redirect to modern OpenCV repositories

## Technical Debt

| Item | Priority | Impact | Effort |
|------|----------|--------|--------|
| VS2013 toolchain (v120) | High | Severely outdated | Low |
| Windows XP support dependency | High | Security risk | Medium |
| No automated builds | High | Reproducibility | Medium |
| No test suite | High | Regression risk | Medium |
| Limited DNN backend support | Medium | Inference performance | Low |
| No CI/CD | Medium | Manual validation | Medium |
| Missing Docker support | Low | Environment consistency | Low |
| No package manager integration | Low | Adoption friction | Low |

## Future Features

| Feature | Description | Priority |
|---------|-------------|----------|
| Migration Guide | VS2013 → VS2022 comprehensive migration | High |
| Enterprise Support Matrix | Deployment scenario compatibility | High |
| Docker Build | Containerized build environment | Medium |
| CI Pipeline | Automated build and test | Medium |
| API Translation Tool | Automated 3.2 → 4.x code migration | Medium |
| ONNX Runtime Examples | DNN module replacement | Medium |
| Archive Release | Final release with EOL documentation | Medium |
| Performance Baselines | Legacy hardware benchmarks | Low |
| Enterprise Contract | Extended support for locked systems | Low |

# Thesis

## Table of contents

- [Thesis](#Thesis)
  - [Table of contents](#Table-of-contents)
  - [Introduction (1-2 pages)](#Introduction-1-2-pages)
  - [Docker overview, motivation, current state of technology](#Docker-overview-motivation-current-state-of-technology)
    - [The Docker project](#The-Docker-project)
  - [Analysis](#Analysis)
    - [Static analysis](#Static-analysis)
    - [Semi-dynamic](#Semi-dynamic)
    - [Dynamic analysis](#Dynamic-analysis)
    - [Hybrid](#Hybrid)
    - [Existing tools and approaches](#Existing-tools-and-approaches)
      - [Image visualization](#Image-visualization)
      - [Security scan](#Security-scan)
      - [Image minimalization](#Image-minimalization)
      - [Image build optimization](#Image-build-optimization)
  - [Related work](#Related-work)
  - [Future work](#Future-work)

---

## Introduction (1-2 pages)

- Image structure, image build process
- Analysis types (static, dynamic, hybrid)
- Aspects of analysis
- Usecases, impacts

(sidenote: target is only linux-x64 based images, no ARM, windowsservercore)

## Docker overview, motivation, current state of technology

### The Docker project

## Analysis

### Static analysis

### Semi-dynamic

### Dynamic analysis

### Hybrid

### Existing tools and approaches

#### Image visualization

- imagelayers: <https://imagelayers.io/>

#### Security scan

- anchore: <https://github.com/anchore/anchore-engine/wiki>
- clair: <https://github.com/coreos/clair>

#### Image minimalization

- distroless: <https://github.com/GoogleCloudPlatform/distroless>
- banyan collector: <https://github.com/banyanops/collector/blob/master/docs/CollectorDetails.md>
- <https://opensource.googleblog.com/2018/01/container-structure-tests-unit-tests.html>

#### Image build optimization

- best practices, bad practices

## Related work

- Missing things
- Integration
- Extension

## Future work

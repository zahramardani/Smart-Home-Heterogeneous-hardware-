# Smart Home: Heterogeneous Hardware Design

Historical smart-home design material from Zahra Mardani Korani's IoT work.

[All projects](https://github.com/zahramardani/ML2PP-Artifacts/blob/main/PROJECTS.md) · [Temperature-monitoring project](https://github.com/zahramardani/Temperature-Monitoring-System)


## Project focus

This repository preserves a smart-home design export associated with heterogeneous hardware modelling. Its role in the portfolio is to provide the original design material for inspection and restoration.

### Review and restoration checklist

| Step | Expected outcome |
|---|---|
| Extract the original archive | A working copy of the deposited design files |
| Identify project metadata | The modelling environment, project type and required plugins |
| Inspect model references | The components and external resources needed to open the design |
| Open the design in its original environment | A basis for documenting the actual architecture and supported operations |

Hardware platforms, communication protocols and deployment results should be established from the recovered design before being described as implemented capabilities. The repository currently provides the original export rather than a verified hardware deployment.


## Repository contents

| File | Purpose |
|---|---|
| [monitoringsystem.design.rar](monitoringsystem.design.rar) | Original compressed design export |
| [README.md](README.md) | Project entry point and archive guidance |

## Inspect the design

1. Download the RAR archive.
2. Extract it into a separate working directory using a RAR-compatible tool.
3. Inspect the extracted files to identify the original modelling tool and its dependencies before importing the design.

The repository currently distributes a design archive. It does not include a documented build procedure, a hardware bill of materials, or an independently runnable application. The archive format alone does not establish which editor or hardware is required.

## Download the original design archive

**[Download `monitoringsystem.design.rar`](https://github.com/zahramardani/Smart-Home-Heterogeneous-hardware-/raw/refs/heads/main/monitoringsystem.design.rar)** (approximately 4.88 KB).

GitHub versions this RAR as an individual binary file. To review or version the models and other files inside it individually, first extract the archive and inspect its contents.

1. Download the file using the direct link above.
2. Extract it using an RAR-compatible utility (for example, Keka or The Unarchiver on macOS, or 7-Zip on Windows).
3. Record the extracted file names and extensions to identify the design format and the original modelling environment. Do not assume a particular editor or hardware platform from the `.design` archive name alone.
4. Once validated and cleared of secrets or third-party restricted content, add the useful extracted design files to a normal project folder, retaining the original archive for provenance.

**Current verification boundary:** the RAR exists in the repository; its internal files, supported editor, and executable or deployment status have not yet been independently verified.

## Related work

- [Temperature Monitoring System](https://github.com/zahramardani/Temperature-Monitoring-System): historical Eclipse/Xtext project material.
- [ML2++ Research Artifacts](https://github.com/zahramardani/ML2PP-Artifacts): later research on model-driven forecasting for IoT/CPS.
- [Forecasting API and SQL portfolio](https://github.com/zahramardani/river_prediction): runnable companion demonstrations.

The original archive is retained at its existing path so historical references remain valid.

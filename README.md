# Hi, I'm Mert Açar

Software developer building web applications, backend systems, and aerospace analysis tools.

I work on REST APIs and responsive interfaces, and I am developing a portfolio of flight-data, simulation, orbital-mechanics and telemetry projects. The engineering models are educational, with their assumptions and validation documented in each repository.

**[Portfolio](https://mertacar-git.github.io/portfolio/)** · **[Interactive aerospace laboratory](https://mertacar-git.github.io/portfolio/lab/index.html)** · **[LinkedIn](https://www.linkedin.com/in/mertacarr/)**

## Aerospace projects

| Project | What it demonstrates | Try it |
|---|---|---|
| [Mission Control](https://github.com/mertacar-git/mission-control) | Concave survey planning, independent boundary validation, ArduCopter SITL/MAVLink, recording and reports | [Demo](https://mertacar-git.github.io/mission-control/) |
| [Flight Telemetry Analyzer](https://github.com/mertacar-git/flight-telemetry-analyzer) | CSV validation, flight plots, threshold analysis and exportable reports | [Demo](https://mertacar-git.github.io/flight-telemetry-analyzer/) |
| [OrbitWatch](https://github.com/mertacar-git/orbitwatch) | SGP4 propagation, ground tracks and observer horizon events | [Demo](https://mertacar-git.github.io/orbitwatch/) |
| [Flight Control Lab](https://github.com/mertacar-git/flight-control-lab) | PID tuning, disturbance response and controller comparison | [Demo](https://mertacar-git.github.io/flight-control-lab/) |
| [Rocket Flight Lab](https://github.com/mertacar-git/rocket-flight-lab) | RK4 integration, changing mass, atmospheric drag and flight-event analysis | [Demo](https://mertacar-git.github.io/rocket-flight-lab/) |
| [Aero Telemetry Protocol](https://github.com/mertacar-git/aero-telemetry-protocol) | Python/C++ codecs, CRC checks, stream recovery and wire compatibility | [Demo](https://mertacar-git.github.io/aero-telemetry-protocol/) |
| [Wing Design Lab](https://github.com/mertacar-git/wing-design-lab) | Parametric wing geometry, analytical lift/drag estimates and NACA profiles | [Demo](https://mertacar-git.github.io/wing-design-lab/) |

Mission Control includes a browser-only demo and a separate local FastAPI/SQLite backend controlling its own ArduCopter SITL session. Real simulator acceptance covers mission execution, connection recovery, hold/resume/RTL and configured low-battery behavior.

Mission Control v1.3 generates routes for concave survey areas and checks complete route segments independently in the backend. Its planning boundary records observed violations without configuring an autopilot geofence. [Survey method and seven-scenario SITL evidence](https://github.com/mertacar-git/mission-control/blob/main/docs/SURVEY_PLANNING.md).

Mission Control v1.4 adds reproducible fault experiments: telemetry interruption/recovery, configured low-battery RTL and GPS-loss EKF LAND. Actual recordings, persistent acceptance reports and synchronized incident investigation connect failures to inspectable evidence. [Experiment definitions and recordings](https://github.com/mertacar-git/mission-control/blob/main/docs/EXPERIMENTS.md).

The [Mission Control engineering case study](https://github.com/mertacar-git/mission-control/blob/main/docs/CASE_STUDY.md) explains reviewed mission uploads, recoverable route editing, command acknowledgment versus observation, and an actual hold-mode defect found and corrected through SITL telemetry. [Captioned walkthrough and evidence](https://github.com/mertacar-git/mission-control/blob/main/docs/media/walkthrough.md).

The browser demos run on-device. The repositories include local Python applications, automated tests, model notes, and actual application screenshots. Browser model outputs are compared against Python reference results; the telemetry library also checks C++/Python packet compatibility.

## Software interests

- REST API design and backend systems with Node.js and Express.
- Responsive web interfaces with JavaScript and React.
- Python data analysis and numerical simulation.
- Binary protocols, testing and reproducible engineering experiments.

## Current direction

I am expanding my software portfolio at the intersection of aviation, space and engineering. My aim is to build understandable tools with runnable demonstrations, documented constraints and meaningful validation.

Projects are developed with AI assistance, and include the validation needed to review and extend their implementations.

## Contact

[GitHub](https://github.com/mertacar-git) · [LinkedIn](https://www.linkedin.com/in/mertacarr/)

# DiRAC 4 Performance profile

- Author(s): 
- Date:
- Application:
- Related DiRAC project:

*Please clone this repository by click the "Use this template" on GitHub.*

## 1. Performance-critical routines
*Please list here routines that typically dominate a production run. Please provide links and references to the code location of this routines, as we as profiler evidence that these routines are indeed dominant. This should be understood as a best-effort analysis to capture most of the time enveloppe from your typical runs, rather than an exhaustive study. Profiler evidence can be from a third-party profiler, as well as custom instrumentation; for the former please describe succintly how profiling is implemented.*

## 2. Theoretical performance expectations
*For all routines identified in the previous section, please provide quantitative theoretical expectations on how well the routine is expected to perform in a best-case scenario. "Performance" is understood here as absolute figures that can be used to constrain hardware specification (e.g. GiB/s, GFlop/s but **not** time-to-solution or speedup relatively to a reference architecture). For example, if the [Roofline Model](https://en.wikipedia.org/wiki/Roofline_model) is an appropriate description for a given routine, providing the arithmetic intensity of the routine is sufficient.*

## 3. Benchmark applications
*Please provide references to the source code of benchmark applications measuring the performances figures described in Sec. 2.*

## 4. Example of benchmark result
*Please provide examples of results obatined from the benchmark described in the previous section. These example are made to be representative of an environment suitable for production, and contributors should not hesitate to choose a favourite, well-known system to obtain these results. Please comment on how well the benchmark results match the theoretical expectations in Sec. 2. If large discrepancies are observed, please comment on you current understading of the root cause, as well as resulting opportunities for future optimisation.*

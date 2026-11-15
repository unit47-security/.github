# UNIT-47

Independent security research and engineering.

We develop research tools and reproducible experiments to understand software failures, investigate vulnerabilities, and test security boundaries.

## Research interests

- Low-level systems, kernels, drivers, and firmware
- Reverse engineering and binary analysis
- Vulnerability research and exploitability assessment
- Fuzzing, crash analysis, and input minimization
- Instrumentation, emulation, and controlled proof-of-concept development
- Web and API authorization testing
- Custom tooling, test harnesses, and research automation

## Projects

Public research tools developed by UNIT-47. Each project has its own maturity level, supported environments, and documented limitations.

### [Ressembly](https://github.com/unit47-security/Ressembly)
**Alpha 0.6.0**

An experimental reverse-engineering and memory-research suite using GDB/Python on Linux x86-64. Includes debugging context, memory inspection, selective allocation tracking, experiment dossiers, and an offline Ghidra bridge. Support is limited to the target configurations documented in the repository.

### [FaultCore](https://github.com/unit47-security/FaultCore)
**v0.1.0 - Laboratory MVP**

A local tool for crash reproduction, signature-preserving input minimization, and structured JSON/text reports. Validated scope is limited to documented laboratory fixtures; a matching crash signature does not establish a shared root cause or confirm a vulnerability.

### [RoleDiff](https://github.com/unit47-security/RoleDiff)
**0.2.0-preview**

Compares JSON API behavior across identities, roles, and tenants against explicit access expectations. Supports human triage and regression tests for manually confirmed authorization cases. Response differences are investigation candidates, not automatic vulnerability confirmations.

## Planned work

**UNIT-47 Toolkit** is a planned collection of focused research utilities, test harnesses, and documented lab exercises. It is not currently presented as a separate published tool.

## Approach

**Reproducible results. Clear evidence. Documented limitations.**

We build tools around specific research problems, document their assumptions, and validate what their results actually demonstrate.

Research and testing are conducted on systems we own or are explicitly authorized to assess.

## Development status

Public repositories are available and development continues. These tools are experimental; publication does not imply production readiness. Consult each repository for its current version, installation instructions, validation evidence, supported environments, and known limitations.

## Join UNIT-47

We are bringing together developers, security researchers, and curious builders who want to explore difficult problems and create original tools.

Bring your own ideas. Propose a research direction, build something experimental, or contribute to an existing project. Our listed projects are starting points, and we welcome ideas beyond our current research interests.

We value technical depth, independent thinking, careful experimentation, and the ability to turn an idea into something others can understand and reproduce.

### Ways to collaborate

We are open to different arrangements, including open-source contributions, paid project work, and potential founding collaborations. Availability and terms will be discussed individually; paid work and founding roles depend on mutual agreement and available resources.

### Introduce yourself

Tell us what you would like to investigate or build. Share relevant code, research, experiments, or a short proposal, and let us know your availability and preferred way to collaborate.

Strong ideas and thoughtful work matter more than a particular title or career path.

Contact: [caltagironefrancesco1993@gmail.com](mailto:caltagironefrancesco1993@gmail.com)

Research and testing must remain within owned or explicitly authorized environments.

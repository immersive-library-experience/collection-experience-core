# Contributing

Issues and pull requests are welcome.

- **Who merges.** TangibleApp maintains `main` of the core and the installation repositories; changes go in
  through pull requests. `main` carries the released state (a tagged release per milestone), `next` the work
  in progress.
- **Interfaces are contracts.** Between the planes (data bundle, sensors, presentation) the documented
  contracts are the interface. Change the contract document and its version with the code; receivers ignore
  fields and addresses they do not know.
- **Licence of contributions.** What you contribute is licensed like the rest: MIT for code, and CC BY 4.0
  for all project results.
- **No content without rights.** Collection content (publications, metadata, images, music and newspaper
  data) comes from its source at build or run time and is never committed. No secrets, tokens or personal
  data either: the sensor services never store or send camera images.
- **Experiments** belong in the [lab](https://github.com/immersive-library-experience/lab) repository; what proves itself is rebuilt here.

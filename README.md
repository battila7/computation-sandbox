<h1 align="center">
  Computation Sandbox
</h1>

<h3 align="center">
  :gear: :parasol_on_ground:
<h3>

<h3 align="center">
  :construction: [WIP] Online simulator for different models of computation, including Reaction Systems and P Systems. 
</h3>

<p align="center">
  <a href="https://github.com/battila7/computation-sandbox/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/battila7/computation-sandbox" alt="computation-sandbox uses The MIT License.">
  </a>
  <a href="https://github.com/battila7/computation-sandbox/actions?query=workflow%3A%22Build+Master%22">
    <img src="https://github.com/battila7/computation-sandbox/workflows/Build%20Master/badge.svg" alt="Master build status.">
  </a>
</p>

> Available at https://battila7.github.io/computation-sandbox

**Table of Contents**

  * [Features](#features)
  * [Up and Running](#up-and-running)
  * [Acknowledgments](#acknowledgments)
  * [Contributing](#contributing)
  * [License](#license)

## Features

> Please note that computation-sandbox is still in its early development phase. The features below are not necessarily available as of now, but will be developed in the near future.

computation-sandbox is a simulator for computational models.

  * **Reaction Systems.** Support for simulating Reaction Systems (refer to [A Tour of Reaction Systems](https://www.researchgate.net/publication/220180605_A_Tour_of_reaction_Systems) for an introduction).
  * **Browser-based.** No installation required, runs straight in your browser.
  * **Offline support.** Can execute without being connected to the internet.
  * **JSON import/export.** Export simulations in JSON format and share/process/import them as you wish.

## Up and Running

Make sure to install [`pnpm`](https://pnpm.io/) beforehand. Then, cd into the `packages/computation-sandbox` directory and issue the following command to run computation-sandbox locally:

```
pnpm run serve
```

## Acknowledgments

This work was supported by the National Research, Development and Innovation Fund of Hungary through project no. K 120558, financed under the K 16 funding scheme.

## Contributing

Contributions, regardless of their type, are always welcome in mvnx! Take a look at the [Contributing Guide](CONTRIBUTING.md) for more information.

## License

Licensed under the [Apache License 2.0](LICENSE).

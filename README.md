# Stan

| **Project Status**                                                               |  **Documentation**                                                               | **Build Status**                                                                                |
|:-------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------:|
|![][project-status-img] | [![][docs-stable-img]][docs-stable-url] [![][docs-dev-img]][docs-dev-url] | ![][CI-build] |

[docs-dev-img]: https://img.shields.io/badge/docs-dev-blue.svg
[docs-dev-url]: https://stanjulia.github.io/Stan.jl/latest

[docs-stable-img]: https://img.shields.io/badge/docs-stable-blue.svg
[docs-stable-url]: https://stanjulia.github.io/Stan.jl/stable

[CI-build]: https://github.com/stanjulia/Stan.jl/workflows/CI/badge.svg?branch=master

[issues-url]: https://github.com/stanjulia/Stan.jl/issues

[project-status-img]: https://img.shields.io/badge/lifecycle-wip-orange.svg

## Purpose

A collection of examples demonstrating to use Stan's cmdstan (as an external program) from Julia. In 2021 I am considering turning the Stan.jl package into a Julia project.

## Background info

The first 2 generations of Stan.jl took a similar approach as the recently released [CmdStanR](https://mc-stan.org/cmdstanr/) and [CmdStanPy](https://github.com/stan-dev/cmdstanpy) options to use Stan's [cmdstan executable](https://mc-stan.org/users/interfaces/cmdstan.html).

Stan.jl v6.x constitutes the third generation and extends Tamas Papp's approach taken in StanRun, StanDump and StanSamples. It covers all of cmdstan's features in separate modules, i.e. StanVariational, StanSample, etc., including an option to run `generate_quantities`.

Stan.jl v6.x will contain examples using the features available in [StanJulia](https://github.com/StanJulia). 

My intention is to continue maintenance of CmdStan.jl for at least another two years (late 2021?).

## Requirements

Stan's cmdstan executable needs to be installed separatedly. Please see [cmdstan installation](https://stanjulia.github.io/Stan.jl/latest/INSTALLATION/). 

For more info on Stan, please go to <http://mc-stan.org>.


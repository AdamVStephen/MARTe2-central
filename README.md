# MARTe2-central

A one stop shop for up to date links to relevant MARTe2 repositories and resources. This is a personal and 
non-exhaustive list of MARTe2 git repositories and tooling.  If you would like to suggest an addition, please make a pull request.

# Core Distribution

The canonical core for a MARTe2 system is to have MARTe2 (by convention cloned as MARTe2-dev) and MARTe2-components.
In addition to these, site/project specific applications may add further elements.

The definitive official source is F4E and the ITER packages delivered for CODAC core system.  The F4E RO, Andre Neto mirrors the F4E internal git repositories on his personal github space.  A number of other MARTe developers have made personal forks from here.

The definitive official UKAEA source is currently tracking the F4E version, but reserves the right to vary since F4E place very tight quality assurance requirements on code that makes it into the core.

| Repo | Provides | Latest Stable | Work in progress |
|:----:|:--------:|:-------------:|:----------------:|
|[MARTe2](https://github.com/AdamVStephen/MARTe2) |MARTe2|main |develop |
|[MARTe2-components](https://github.com/AdamVStephen/MARTe2-components) |MARTe2-components|main |develop |

# Add-on Packages and Unofficial Utilities

The following repositories provide example applications and tooling that is useful for getting started with
MARTe2 projects.  They are generally unofficial and unsupported but every effort to keep them compatible
with the evolving core shall be made.

| Repo | Provides | Latest Stable | Work in progress |
|:----:|:--------:|:-------------:|:----------------:|
|[MARTe2-doctools](https://github.com/AdamVStephen/MARTe2-doctools) |CfgTo tools |main |barrhead |
|[MARTe2-demos-sigtools](https://github.com/AdamVStephen/MARTe2-demos-sigtools) |Signal demos|main |barrhead |
|[MARTe2-utils](https://github.com/AdamVStephen/MARTe2-utils) |Baseline MARTe2-dev + components|main |barrhead |
|[marte2_codegen](https://github.com/AdamVStephen/marte2_codegen) |Cookiecutter templates|main |barrhead |

# Deprecated Repos

Earlier work on the above is now deprecated because it too tightly couples combinations of packages
which leads to inefficiency in being able to create docker images.

| Repo | Provides | Latest Stable | Work in progress |
|:----:|:--------:|:-------------:|:----------------:|
|[MARTe2-sigtools](https://github.com/AdamVStephen/MARTe2-sigtools) |Integrates utils and demos-sigtools|main |barrhead |

#

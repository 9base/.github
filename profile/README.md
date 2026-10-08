# 9base

Independent engineering archive and laboratory by [Süleyman Poyraz (@Zaryob)](https://github.com/Zaryob).

9base brings together embedded and platform engineering, scientific software, systems tooling and the projects built while learning. Some repositories carry local engineering work; others preserve the upstream tools and source that supported it.

The collection is organized by both technical area and maintenance status, so visitors can find the work, understand its origin and see what is still maintained.

Not every repository under 9base was authored by 9base. Some are upstream projects, dependencies, working forks or historical snapshots. Each repository documents its provenance, verified local changes and maintenance status; upstream authors retain credit for their work.

## Maintained downstream and working copies

| Repository | Status | Scope |
| --- | --- | --- |
| [qFlipper](https://github.com/9base/qFlipper) | Maintained Downstream | Device-information compatibility patch and observed upstream synchronization. |
| [gdb-dashboard](https://github.com/9base/gdb-dashboard) | Working Copy | Retained open for debugger/tooling work; audited source matched upstream. |
| [jsbsim](https://github.com/9base/jsbsim) | Working Copy | Retained open with a historical C130 model adjustment on `master_changed`. |

“Open” describes the repository’s administrative state. Working Copy does not imply ongoing maintenance: current use, integration and a synchronization schedule have not been verified for those two copies. qFlipper has a verified local compatibility patch and a recent upstream merge.

## Embedded and platform engineering

The [Tinker Board 2 family](https://github.com/9base/Tinkerboard2-kernel) preserves vendor BSP components: Linux kernel, U-Boot, Buildroot, Debian rootfs tooling, Rockchip binaries, Linux and Android manifests, and Yocto/Poky. The repositories cross-link their roles and upstreams. Their Preserved classification distinguishes vendor engineering from the limited verified local filename fix and README experiment.

[nvidia_stuff](https://github.com/9base/nvidia_stuff) is a Historical index of Jetson/NVIDIA launcher scripts and installation notes, with vendor frameworks credited separately.

## Systems and developer tooling

The [Open License Manager family](https://github.com/9base/licensecc) retains upstream licensing tools, generator, dependencies and examples as Preserved repositories.

Historical Downstream repositories record substantive past adaptations without promising current maintenance. Examples include [chm2pdf](https://github.com/9base/chm2pdf), [flowgen](https://github.com/9base/flowgen), [Veil](https://github.com/9base/Veil) and [torshammer](https://github.com/9base/torshammer). Their documentation separates the verified local changes from the original upstream code.

## Research and scientific software

The ConVarT family connects [ConVarT_Web](https://github.com/9base/ConVarT_Web), a Historical Downstream with verified local development, the Preserved [ConVarT_pipeline](https://github.com/9base/ConVarT_pipeline), and Historical [ConvartDataGenerate](https://github.com/9base/ConvartDataGenerate) scripts. The family documentation distinguishes Kaplan Lab upstream research and software from the recorded local work.

## Historical original projects and learning

[Rayban](https://github.com/9base/Rayban) documents a 2021 internship WinForms application for a TÜRASAŞ wheel test unit, with a retrospective bounded by the retained source and public project context.

Educational archives include [AndroGarbage](https://github.com/9base/AndroGarbage), [FlutterGarbage](https://github.com/9base/FlutterGarbage), [moviepad](https://github.com/9base/moviepad), [mysqlogin](https://github.com/9base/mysqlogin) and [rolling_cat](https://github.com/9base/rolling_cat). They retain their coursework, learning and experimental scope.

## How repository status works

| Status | Meaning |
| --- | --- |
| Maintained | Original work or organization documentation receiving current upkeep. |
| Maintained Downstream | Upstream-derived software with verified local work and current maintenance evidence. |
| Working Copy | A copy intentionally kept open for possible work; ongoing maintenance is not asserted. |
| Historical | Original work retained for its past engineering context. |
| Historical Downstream | Upstream-derived work with substantive verified local adaptations, now retired. |
| Preserved | Upstream source, dependencies or snapshots retained with attribution. |
| Educational | Coursework, learning projects and experiments. |

Each software repository has one primary status, also expressed as a topic. The profile repository uses Maintained for organization documentation.

## Preserved open source

Repositories such as [MS-DOS](https://github.com/9base/MS-DOS), [librsvg](https://github.com/9base/librsvg) and [wubi](https://github.com/9base/wubi) preserve upstream source and attribution. Archival custody does not imply 9base authorship or ongoing support.

Historical, Historical Downstream, Preserved and Educational repositories are archived. Reconstructed retrospective documentation is labeled in each repository; its historical placement does not imply that new technical work occurred then. Refer to individual README files for evidence and limitations.

---

**Profile repository status: Maintained organization documentation.** Updated 8 October 2026 after repository-level curation.

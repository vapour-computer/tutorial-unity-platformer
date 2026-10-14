# Vapour files for Unity

This branch of [2D-Platformer-Hunter](https://github.com/ta-david-yu/2D-Platformer-Hunter) (MIT) is the sample for the
**Unity tutorial** in the [Vapour handbook](https://vapour-computer.github.io/vapour-dev-docs/).

The repository is a Unity **package**, not a full project, so it cannot be built on its own. This folder (the `~` makes
Unity ignore it) holds the files you copy into a Unity project that uses the package:

| File | Copy it to |
| --- | --- |
| `Assets/Editor/VapourBuild.cs` | `Assets/Editor/VapourBuild.cs` in your project (the same script `vapour create --engine unity` writes) |
| `vapour.toml` | the project root |
| `vapour-publish.yml` | `.github/workflows/vapour-publish.yml` |

**Status:** nothing here has been built by us. We had no Unity editor or license. The handbook tutorial says so too.

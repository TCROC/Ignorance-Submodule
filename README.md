# Ignorance-Submodule

This repository formats tags nightly from the Ignorance repository here: https://github.com/SoftwareGuy/Ignorance so that they can be added as a submodule to a Unity project.  To add it to your project, use this template of commands:

```sh
git submodule add https://github.com/TCROC/Ignorance-Submodule.git Assets/[path to submodule]
cd Assets/[path to submodule]
git checkout [tag version]
```

For example:

```sh
git submodule add https://github.com/TCROC/Ignorance-Submodule.git Assets/Submodules/Ignorance
cd Assets/Submodules/Ignorance
git checkout 1.3.9-2
```

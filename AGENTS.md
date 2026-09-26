# Kitchenplan Configuration Instructions

`Cheffile` pins cookbooks; `config/default.yml`, group files, and person-specific configuration determine which macOS workstations receive a setting. Trace that inheritance before changing a package, preference, or group assignment, and name the affected host or group in the change.

There is no repository manifest or automated validation command. `tmp/librarian/cache/` is generated cookbook cache, not configuration source. Completion for a configuration edit is a narrowly inspected YAML/Cheffile diff with the target scope identified; do not run a workstation bootstrap just to validate an instruction or YAML change.

# Angular Control Flow Migration Bug Reproduction

Step to reproduce

1. Run `nx generate @angular/core:control-flow-migration --path=libs/mylib`

Observations

1. The schematic is finding an incorrect tsconfig file. It is finding `apps/ng-control-flow-mig-repro/tsconfig.app.json`

Error

```
SchematicsException [Error]: Could not find any files to migrate under the path /<snip>/ng-control-flow-mig-repro/libs/mylib. Cannot run the control flow migration.
```

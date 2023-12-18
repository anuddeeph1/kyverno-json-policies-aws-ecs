<ins>**Commands:**</ins>
- Make sure you have `kyverno-json` installed on the machine 
- `kyverno-json scan --policy validate-ecs-resource-tag.yaml --payload null-bad-payload.json   --pre-process "planned_values.root_module.resources`
- `kyverno-json scan --policy validate-ecs-resource-tag.yaml --payload bad-payload.json   --pre-process "planned_values.root_module.resources`
- `kyverno-json scan --policy validate-ecs-resource-tag.yaml --payload good-payload.json   --pre-process "planned_values.root_module.resources`




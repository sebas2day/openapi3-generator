{{#if openapi.components.schemas}}
## Schemas

{{#each openapi.components.schemas}}
  {{~>schema schema=. schemaName=@key~}}
{{/each}}
{{/if}}
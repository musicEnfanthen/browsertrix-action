# browsertrix-action

A Github action that runs a browsertrix crawler. Used in the context of SUCHO (https://www.sucho.org/)

The action can be triggered manually by entering a url in the "Run workflow" dropdown here: [../actions/workflows/main.yml](https://github.com/musicEnfanthen/browsertrix-action/actions/workflows/main.yml)

## Limitations

According to [official documentation](https://docs.microsoft.com/en-us/azure/devops/pipelines/agents/hosted?view=azure-devops&tabs=yaml#capabilities-and-limitations), public GH actions are limited to 10 parallel jobs for a maximum of 6h each, and 10GB of storage for source and build outputs.



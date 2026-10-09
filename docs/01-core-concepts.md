# Core concepts

- Workflow: a set of connected nodes that automates a task.
- Trigger: the node that starts a workflow (manual, schedule, webhook, app event).
- Node: a single step, such as calling an API or transforming data.
- Item: n8n passes data between nodes as a list of JSON items.
- Expression: dynamic values like $json.field wrapped in double curly braces that read data from earlier nodes.
- Credential: stored authentication used by nodes to reach external services.
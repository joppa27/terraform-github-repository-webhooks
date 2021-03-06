
## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| active | Indicate of the webhook should receive events. | string | `true` | no |
| enabled | Whether or not to enable this module | string | `true` | no |
| events | A list of events which should trigger the webhook. | list | `<list>` | no |
| github_organization | GitHub organization to use when creating webhook | string | - | yes |
| github_repositories | List of repository names which should be associated with the webhook | list | `<list>` | no |
| github_token | GitHub token used for API access | string | - | yes |
| name | The type of webhook | string | `web` | no |
| webhook_content_type | Webhook Content Type (E.g. application/json) | string | `application/json` | no |
| webhook_insecure_ssl | Webhook Insecure SSL (E.g. trust self-signed certificates) | string | `false` | no |
| webhook_secret | Webhook secret | string | `` | no |
| webhook_url | Webhook URL | string | - | yes |


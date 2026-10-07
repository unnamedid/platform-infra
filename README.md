# platform-infra

Owned by the **platform team**. Argo CD configuration for the whole platform:

| Folder | What lives here |
|---|---|
| `bootstrap/` | The root Application and the one-time spoke bootstrap manifests |
| `projects/` | `AppProject`s: who may deploy what, from where, to which cluster |
| `apps/` | Child Applications of the root app (app-of-apps) |
| `applicationsets/` | Generators that stamp out one Application per service x cluster |

Repository: https://github.com/unnamedid/platform-infra

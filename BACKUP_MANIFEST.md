# Excluded files and history

- `predictive_maintenance.csv` (531,014 bytes): training dataset, excluded from the public repository.
- The original Git history is not included in this sanitized snapshot because an older commit contains generated npm cache entries with credential-shaped Basic-Auth URLs. The original repository and history remain unchanged on the cluster.
- `node_modules/`, `.next/`, Python environments/caches, local service data, logs, and Node-RED credential files are ignored by `.gitignore`.

No local `node_modules`, service data, or log directories were present in the current checkout when this snapshot was prepared. Rotate any credentials represented by the historical URLs if they were real and remain active.
- `node_red/.config.runtime.json`, `.config.users.json`, and `.config.nodes.json`: Node-RED generated runtime/user/module state; the runtime file includes a credential-secret field, so all three are omitted.

# The problem
When you order an HVI connection, some of the configuration options show technical names (like "Avtalt MTU") instead of the friendlier wording we settled on.
When you later look at the agreement, the configuration section shows the raw technical names again, so the friendly names you saw while ordering are gone.

# Scope
This change covers how Koble displays configuration names and values when customers order an HVI connection and view the agreement.
Other order pages that share these labels are also in scope.

The backend and Plexus are unchanged.

# Roadmap
- refactor: separate HVI configuration labels from shared defaults
- feat: show friendly configuration names on HVI order page
- feat: show friendly configuration value labels on HVI order page
- feat: show friendly configuration names and values on HVI agreement page

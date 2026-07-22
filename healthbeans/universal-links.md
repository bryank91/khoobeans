# Universal Links for HealthBeans iOS app
This repository hosts the `apple-app-site-association` files that let the
HealthBeans iOS app open the meal camera directly from
`https://bryank91.github.io/khoobeans/healthbeans/meal`.

Apple fetches the file anonymously from any of these locations:

- `/.well-known/apple-app-site-association` (preferred, current iOS)
- `/apple-app-site-association` (fallback for older iOS)

Updating the AASA does not require a new app build — iOS re-checks
periodically. The next time the user opens HealthBeans (or after a
device restart) the new association is picked up.

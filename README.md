# Test Game

A tiny browser game used to test automatic deployments from GitHub to itch.io.

## Play

Use **WASD** or the **arrow keys** to move. Collect stars and avoid the red hunters.

## Deployment

Every push to `main` runs `.github/workflows/deploy-itch.yml`, which publishes the web build to the itch.io `web` channel using the repository secret `BUTLER_API_KEY`.

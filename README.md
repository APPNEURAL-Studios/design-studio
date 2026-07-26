# Design Studio

Canvas, image, vector, brand, infographic

Create graphics with canvas, photo, vector, and pixel-art editors. Design logos, icons, banners, posters, and infographics, then manage brand kits, design tokens, themes, and style guides to keep every asset on-brand.

## Microservices Used

**Platform baseline** (common to every app & studio): `gateway-service`, `authentication-service`, `identity-service`, `access-service`, `security-service`, `audit-service`, `observability-service`, `control-service`, `deployment-service`, `integration-service`, `storage-service`, `reporting-service`, `analytics-service`, `notification-service`

**Functional services (7):**

| Service | Status |
|---|---|
| `media-service` | New (Tier-1) |
| `publishing-service` | Core |
| `document-service` | Core |
| `agent-service` | Core |
| `model-service` | Core |
| `asset-service` | Suggested — not yet built |
| `collaboration-service` | Suggested — not yet built |

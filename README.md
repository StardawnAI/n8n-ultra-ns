# N8N-ADVANCED-NS 🚀 (Pre-Release/Next)

Pre-release version of n8n-advanced with custom nodes. Based on n8n's latest pre-release/next version.

## Quick Start

```bash
# Latest pre-release version
docker pull stardawn/n8n-advanced-ns:latest
docker run -d -p 5678:5678 stardawn/n8n-advanced-ns:latest

# Or use the :next tag
docker pull stardawn/n8n-advanced-ns:next

# Alternative: GitHub Container Registry
docker pull ghcr.io/stardawnai/n8n-advanced-ns:latest
```

**Available Tags:**
- `:latest` / `:next` - Latest pre-release version
- `:X.X.X-stardawn-X.X` - Specific version (e.g., `2.3.0-stardawn-1.0`)

Access at: http://localhost:5678

## What's Included

- **Base:** n8n pre-release/next version (latest features, may be unstable)
- **Custom Nodes:** Remberg, WhatsApp Private
- **Auto-Sync:** Automatically syncs with latest n8n pre-releases

## Difference to n8n-advanced (stable)

| Feature | n8n-advanced | n8n-advanced-ns |
|---------|--------------|-----------------|
| n8n Version | Stable release | Pre-release/Next |
| Python Support | ✅ | ❌ |
| PostgreSQL Setup | ✅ | ❌ |
| Custom Nodes | ✅ | ✅ |
| Stability | Production-ready | Experimental |

## For Stable Version

Use [n8n-advanced](https://github.com/StardawnAI/n8n-advanced) for production deployments.

```bash
docker pull stardawn/n8n-advanced:latest
```

# Clash YAML for Hugging Face

This repository contains a Clash configuration file (`huggingface.yaml`) for proxying Hugging Face traffic.

## Configuration

The following domains are included in the configuration:

```yaml
payload:
  - DOMAIN-SUFFIX,huggingface.co
  - DOMAIN-SUFFIX,hf.co
  - DOMAIN-SUFFIX,cas-bridge.xethub.hf.co

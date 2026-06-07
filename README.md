# gora

The open source AI coding agent.

## Install

```bash
curl -fsSL https://goraland.github.io/install | bash
```

## Quick start

```bash
export OPENAI_API_KEY=your-key-here
gora run 'Hello, world!'
```

## Verify downloads

Releases are signed with PGP. To verify:

```bash
gpg --auto-key-locate keyserver --keyserver hkps://keyserver.ubuntu.com --locate-keys goraland@users.noreply.github.com
gpg --verify gora_linux_amd64.tar.gz.asc gora_linux_amd64.tar.gz
```

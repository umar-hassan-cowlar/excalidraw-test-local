# Excalidraw(forked)

## Branch management

```
upstream(excalidraw/excalidraw):
    release tag

fork:
    fork: alias to latest stable forked, rebased always
    release/$(version)-$(minor-build-version): based on upstream release tag, and merge with features
    feat/$(name): feature branch, maybe deleted
    feat/$(name)-rebase-$(date): feature branch, with new upstream rebased
```

## Current active feature branch

- feat/chinese-font-support (active)
  - feat/chinese-font (deprecated)
  - feat/chinese-font-for-v0.12.0 (deprecated, merged to release)
- feat/self-host-backend-origin
  - feat/self-host-backend (deprecated)
  - feat/self-host-new-pr-for-v0.12.0 (deprecated, merge to release)
  - feat/self-host-backend-origin-v0.14.2 (active)


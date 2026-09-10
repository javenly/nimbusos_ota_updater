# NimbusOS OTA Update Server

This repository hosts the static JSON endpoints for the built-in Updater app (`packages/apps/Updater`) on NimbusOS. It delivers seamless over-the-air system updates for supported devices using GitHub Pages and GitHub Releases.

---

## 🚀 Endpoint Structure

The NimbusOS Updater queries endpoints following this URL schema:

```text
https://<username>.github.io/<repo>/v1/{device}/{build_type}/{incremental_version}

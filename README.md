## App Helm Charts

Inspired By:

https://www.opcito.com/blogs/creating-helm-repository-using-github-pages

Usage:

```bash
helm repo add app-helms https://lordrahl90.github.io/app-helms
helm repo update
```

Deploy Notes

```bash
helm install notes app-helms/notes
```

Deploy Shipments

```bash
helm install shipments app-helms/shipments
```
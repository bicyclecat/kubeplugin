# Custom kubectl plugin for viewing cluster statistics

## Usage:
In order to use this plugin, first of all you need to place the file to a directory, listed in your PATH environment variable. Then, you can enter commands like:
```bash
kubectl kubeplugin <RESOURCE_TYPE> <NAMESPACE>
```

### Command examples:

```bash
kubectl kubeplugin nodes kube-system
```

```bash
kubectl kubeplugin pods kube-system
```
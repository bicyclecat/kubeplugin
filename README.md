# Custom kubectl plugin for viewing cluster statistics

## Usage:
In order to avoid possible errors using this plugin, first of all you need to place the file to a directory, listed in your PATH environment variable. Then, you can enter commands like:
```bash
kubeplugin <RESOURCE_TYPE> <NAMESPACE>
```

### Command examples:

```bash
kubeplugin nodes kube-system
```

```bash
kubeplugin pods kube-system
```
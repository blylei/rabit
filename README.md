# rabit
A client agent that execute remote command submitted by Frabit.
The major command include:
- backup
- restore
- sync
- pull-binlog

### Make a backup
```bash
rabit backup --optins
```

### Restore a backup
```bash
rabit restore --optins
```

### Transfer backup files from local-IDC into remote-IDC
```bash
rabit sync --optins
```

### Pull binlog from mysql instance
```bash
rabit pull-binlog --optins
```
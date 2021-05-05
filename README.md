# rabit
A client agent that execute remote command submitted by Frabit.
The major command include:
- backup
- restore
- sync
- pull-binlog

## 1、Install
pip
```
pip install rabit
```
build install from source code
```
git clone https://github.com/blylei/rabit.git
cd rabit
python setup.py install
```
## 2、Use case
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
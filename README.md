serve-php
=========

```bash
cat ../stacks/static/Dockerfile | sed 's/\${\{0,1\}DOCUMENT_ROOT}\{0,1\}/public/' | sudo docker buil
d -t test -
```

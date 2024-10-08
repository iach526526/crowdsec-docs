---
id: cscli_contexts_remove
title: cscli contexts remove
---
## cscli contexts remove

Remove given context(s)

### Synopsis

Remove one or more contexts

```
cscli contexts remove [item]... [flags]
```

### Examples

```
cscli contexts remove crowdsecurity/yyy crowdsecurity/zzz
```

### Options

```
      --all     Remove all the contexts
      --force   Force remove: remove tainted and outdated files
  -h, --help    help for remove
      --purge   Delete source file too
```

### Options inherited from parent commands

```
      --color string    Output color: yes, no, auto (default "auto")
  -c, --config string   path to crowdsec config file (default "/etc/crowdsec/config.yaml")
      --debug           Set logging to debug
      --error           Set logging to error
      --info            Set logging to info
  -o, --output string   Output format: human, json, raw
      --trace           Set logging to trace
      --warning         Set logging to warning
```

### SEE ALSO

* [cscli contexts](/cscli/cscli_contexts.md)	 - Manage hub contexts


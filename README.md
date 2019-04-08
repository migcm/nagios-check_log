# nagios-check_log

Check if there is a certain text in a log file.
* The plugin will return WARNING status if a certain word is found in the indicated log.
* The plugin will return CRITICAL status if a certain word is found in the indicated log.

### Syntax:
```check_log Word_to_search_warning_state Word_to_search_critical_state log_file```

### Examples:

```check_log WARNING CRITICAL /var/log/nginx/access.log```

```check_log '404' '193.123.215.5' /var/log/nginx/access.log```

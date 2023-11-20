# Weidu mod list

Weidu log for bg1ee, bg2ee, iwdee, pre-eet bg1 and eet. Note EET log order is **heavily** borrowed from, @morpheus562.

## How to compare me

```sh
grep -vxFf  <(cat user-submitted-weidu-logs/dark0dave/current_bg2_weidu.log | awk '{print $1$2$3}') <(cat <target_log_to_compare> < | awk '{print $1$2$3}')
```
where <target_log_to_compare> is the log you wish to compare my current_bg2_weidu.log too.

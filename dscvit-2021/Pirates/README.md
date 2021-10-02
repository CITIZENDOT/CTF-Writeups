# Pirates

## Statement

![Challenge Description](chall.png)

## Approach

I think we're supposed to use WireShark and search for packet detils. Anyway, grep has done it :)

```bash
grep -aoiE 'dsc\{\w*\}' network_listen.pcap
```

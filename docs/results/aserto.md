---
sidebar_position: 1
---

# Aserto

Interop results for the Aserto implementation hosted at https://authzen-proxy.demo.aserto.com.

## Test results

```bash
yarn test https://authzen-proxy.demo.aserto.com
yarn run v1.22.19
$ ./scripts/test.sh https://authzen-proxy.demo.aserto.com
>>> checking decisions
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_read_user"},"resource":{"id":"beth@the-smiths.com"}}
PASS REQ:{"subject":{"identity":"CiRmZDA2MTRkMy1jMzlhLTQ3ODEtYjdiZC04Yjk2ZjVhNTEwMGQSBWxvY2Fs"},"action":{"name":"can_delete_todo"},"resource":{"ownerID":"beth@the-smiths.com"}}
<<< done checking decisions
```

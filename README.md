# php-web-dir-scan
PHP WEB DIR SCAN 

A tool that will help you find access to unwanted folders and files that are forgotten or found open on websites.

## Params

| Param      | Description |
| --------- | -----:|
|  --u  | Target site url|
|  --show | Show pages with response httpcode|
| --hide | Hide pages with response httpcode|
| --random-agent | Set random agent per request |



## Example

```bash
  php dir --u "http(s)://example.com" --show 200,301 --random-agent
```

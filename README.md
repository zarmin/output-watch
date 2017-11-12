# output-watch

CLI wrapper to kill a subprocess if it doesn't output for a while

## Example

```
./output_watch 10 sleep 600
# ... after 10 seconds
# No output for 10 seconds... Exiting!
# Exit code will be 3
```

## Deps

- No external dependencies
- Python 2.7


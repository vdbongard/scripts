# Scripts

A small collection of useful scripts for automating repetitive manual tasks.
It includes practical helpers to speed up day-to-day workflows.

## Install scripts to PATH

To run scripts directly from anywhere, copy files from this repo's `bin/` directory into `/usr/local/bin/`.

```bash
sudo cp /path/to/scripts/bin/* /usr/local/bin/
```

Then make sure all copied scripts are executable:

```bash
for f in /usr/local/bin/*; do
  sudo chmod +x "/usr/local/bin/$(basename "$f")"
done
```

After that, you can call the script directly from your shell:

```bash
proto-sync-asdf
```

# Dotfiles to dropbox

Backup some dotfiles to my dropbox folder.

Inspired by Urres [system-backup-list](https://github.com/urre/system-backup-list).

## Crontab

Run every 4 hour

```bash
0 */4 * * * /path-to/dotfilesbackup > /dev/null 2>&1
```

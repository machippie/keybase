
## Default Variables

### keybase_started

Start in background after install

#### Default value

```yaml
keybase_started: true
```

### keybase_user

User to run user-specific commands

#### Default value

```yaml
keybase_user | default(homebrew_user) | default(ansible_user_id)
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger

# Heading 1
## Heading 2

> Quote

Message

### Heading 3

!!! note
Test

```java
ProxyServer.getInstance().getPlayers().stream()
    .filter(p -> p.hasPermission(Permissions.BAN_RECEIVE))
    .forEach(p -> p.sendMessage(TextComponent.fromLegacyText(translateColorCodes(alertMessage))));
```

# Powershell

## Download file

```powershell
$ Invoke-WebRequest <url>
```

## Execute file

```powershell
$ Start-Process <exe>
$ .\<exe>
```

## Firewall interraction

```powershell
$ Get-NetFirewallProfile | ft Name,Enabled
```

---

# CMD

## Firewall interraction

```cmd
# Check status
$ netsh advfirewall show allprofiles state
# Disable FW
$ netsh advfirewall set allprofiles state off
# Allow FW
$ netsh advfirewall set allprofiles state on
```

## Download content

```cmd
$ wget <ip>
$ curl <ip>
$ Invoke-WebRequest <url>
```

## Execute exe

```cmd
$ start <name_process>
```

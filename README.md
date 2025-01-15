# Security-log Realtime History
```code
Visibility: Show code on vscode by Microsoft with process by Github realtime seccurity-log history (Applies to all profiles)
```
```code
Built-in Security: (Applies to all profiles)
```
```code
Security: Restrict UNCAccess (Applies to all profiles)
```
If enabled, only allows access to UNC host names that are allowed by the Security: Allowed UNCHosts setting or after user confirmation.
Find out more about this setting at https://aka.ms/vscode-windows-unc , https://github.com/enterprise/advanced-security , https://github.com/security
``` code
Security > Workspace or Workflow > Trust: Empty Window (Applies to all profiles)
```
Controls whether or not the empty window is trusted by default within VS Code.
When used with Security > Workspace > Trust: Untrusted Files, you can enable the full functionality of VS Code without prompting in an empty window.
A set of UNC host names (without leading or trailing backslash, for example 192.168.0.1 or my-server)
to allow without user confirmation. If a UNC host is being accessed that is not allowed via this setting or has not been acknowledged via user confirmation, an error will occur and the operation stopped. A restart is required when changing this setting. Find out more about this setting at https://aka.ms/vscode-windows-unc , https://github.com/enterprise/advanced-security , https://github.com/security

# fastfetch

personal fastfetch config.

## preview

<!-- screenshot -->
![preview](https://imgur.com/d1Oqx4l.png)
## setup

put `fastfetch/config.jsonc` and `fastfetch/ascii.txt` in `C:\Users\%username%\.config\fastfetch\`

## deps

- [fastfetch](https://github.com/fastfetch-cli/fastfetch) — `winget install fastfetch`
- windows terminal


# faq
If you're getting this message
```
. : File C:\Users\pov\Documents\WindowsPowerShell\profile.ps1 cannot be loaded because running scripts is disabled on
this system. For more information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:3
+ . 'C:\Users\pov\Documents\WindowsPowerShell\profile.ps1'
+   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess
```

simply run this to fix:

```Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser```

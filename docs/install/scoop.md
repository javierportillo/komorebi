## Installing with Scoop

It highly recommended that you enable support for long paths in Windows by running the following command in an Administrator Terminal before installing komorebi.

```powershell
Set-ItemProperty 'HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem' -Name 'LongPathsEnabled' -Value 1
```
### Add the Extras bucket
```
scoop bucket add extras
```

### Install komorebi and whkd

This command installs `komorebi` and `whkd`.
```
scoop install komorebi whkd
```

Once komorebi is installed, proceed to get the [example configurations](../getting-started.html#getting-example-configurations).
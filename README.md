# SELinux-NagiosXI

<!-- This is commented out. -->

<details>
 <summary>Summary</summary>

```
solution: mysolution
```
</details>

example
```
NAME=nagios_logrotate
checkmodule -M -m -o $NAME.mod $NAME.te
semodule_package -o $NAME.pp -m $NAME.mod

semodule -i $NAME.pp

```

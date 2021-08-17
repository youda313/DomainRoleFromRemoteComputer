# DomainRoleFromRemoteComputer
Get domain role and PC type from remote computers


How to use it?:

Get-DomainRole -Computername DC01
(GC "c:\users\$env:username\desktop\list.txt") | % {Get-DomainRole -Computername $_}

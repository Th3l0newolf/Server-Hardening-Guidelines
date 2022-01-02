1.9|Security Options |Setting
:-----:|:-----:|:-----:
1.9.1 |Network security: Minimum session security for NTLM SSP based (including secure RPC) servers |For all profiles, the recommended state for this setting is Requir|e NTLMv2 session security, Require 128-bit encryption.
1.9.2| Network access: Remotely accessible registry paths and sub-paths |	For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is:System\CurrentControlSet\Control\Print\Printers System\CurrentControlSet\Services\EventlogSoftware\Microsoft\OLAP ServerSoftware\Microsoft\Windows NT\CurrentVersion\PrintSoftware\Microsoft\Windows NT\CurrentVersion\WindowsSystem\CurrentControlSet\Control\ContentIndex System\CurrentControlSet\Control\Terminal Server System\CurrentControlSet\Control\Terminal Server\UserConfig System\CurrentControlSet\Control\Terminal Server\DefaultUserConfiguration Software\Microsoft\Windows NT\CurrentVersion\Perflib System\Curr|entControlSet\Services\SysmonLogOther Domain Controller profile(s), are Not Defined.
1.9.3 |Accounts: Rename administrator account |For all profiles, the recommended state for this setting is any value that does not contain the term "admin".
1.9.4 |Accounts: Rename guest account|For all profiles, the recommended state for this setting is any value that does not contain the term "guest".
1.9.5 |Accounts: Guest account status |Disabled
1.9.6 |Network access: Allow anonymous SID/Name translation |Disabled
1.9.7 |Accounts: Limit local account use of blank passwords to console logon only |Enabled
1.9.8 |Devices: Allowed to format and eject removable media |Administrators
1.9.9 |Devices: Prevent users from installing printer drivers |Enabled
1.9.10|Devices: Restrict CD-ROM access to locally logged-on user only |For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is Enabled.For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is Not Defined.
1.9.11 |Devices: Restrict floppy access to locally logged-on user only |For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is Enabled.For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is Not Defined.
1.9.12 |Domain member: Digitally encrypt or sign secure channel data (always) |Enabled
1.9.13 |Domain member: Digitally encrypt secure channel data (when possible) |Enabled
1.9.14 |Domain member: Digitally sign secure channel data (when possible) |Enabled
1.9.15 |Domain member: Disable machine account password changes |Disabled
1.9.16 |Domain member: Maximum machine account password age |For all profiles, the recommended state for this setting is 30 day(s).
1.9.17 |Domain member: Require strong (Windows 2000 or later) session key |Enabled
1.9.18 |Domain controller: Allow server operators to schedule tasks|For the Enterprise Domain Controller and SSLF Domain Controller profile(s), the recommended value is Disabled.For the Enterprise Member Server and SSLF Member Server profile(s), the recommended value is Not Defined.
1.9.19 |Domain controller: LDAP server signing requirements |For the SSLF Domain Controller profile(s), the recommended value is Require signing.For the Enterprise Member Server, Enterprise Domain Controller and SSLF Member Server profile(s), the recommended value is Not Defined.
1.9.20 |Domain controller: Refuse machine account password changes |For the Enterprise Domain Controller and SSLF Domain Controller profile(s), the recommended value is Disabled.For the Enterprise Member Server and SSLF Member Server profile(s), the recommended value is Not Defined.

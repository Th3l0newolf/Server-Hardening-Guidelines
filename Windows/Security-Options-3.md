1.9.41 |Network access: Named Pipes that can be accessed anonymously|For the SSLF Member Server profile(s), the recommended value is browser.For the SSLF Domain Controller profile(s), the recommended value is: netlogon, lsarpc, samr, browser.For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is Not Defined.
:-----:|:-----:|:-----:
1.9.42 	|Network access: Remotely accessible registry paths |For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is Not Defined.For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is:System\CurrentControlSet\Control\ProductOptionsSystem\CurrentControlSet\Control\Server ApplicationsSoftware\Microsoft\Windows NT\CurrentVersion
1.9.43 	|Network access: Restrict anonymous access to Named Pipes and Shares |Enabled
1.9.44 	|Network access: Shares that can be accessed anonymously |None
1.9.45 	|Network access: Sharing and security model for local accounts |For all profiles, the recommended state for this setting is Classic - local users authenticate as themselves.
1.9.46 	|Network security: Do not store LAN Manager hash value on next password change |Enabled
1.9.47 	|Network security: LAN Manager authentication level|For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is Send NTLMv2 response only. Refuse LM.For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is Send NTLMv2 response only. Refuse LM & NTLM.
1.9.48 	|Network security: LDAP client signing requirements |Negotiate signing
1.9.49 	|Network security: Minimum session security for NTLM SSP based (including secure RPC) clients |Require NTLMv2 session security, Require 128-bit encryption
1.9.50 	|Recovery console: Allow automatic administrative logon |Disabled
1.9.51 	|Recovery console: Allow floppy copy and access to all drives and all folders |For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is Disabled.For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is Not Defined.
1.9.52 	|Shutdown: Clear virtual memory pagefile |Disabled
1.9.53 	|Shutdown: Allow system to be shut down without having to log on |Disabled
1.9.54 |System objects: Require case insensitivity for non-Windows subsystems |Enabled
1.9.55 	|System objects: Strengthen default permissions of internal system objects (e.g. Symbolic Links)|Enabled
1.9.56 	|System cryptography: Force strong key protection for user keys stored on the computer |For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is User must enter a password each time they use a key.For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is User is prompted when the key is first used.
1.9.57 	|System settings: Optional subsystems |None
1.9.58 	|System settings: Use Certificate Rules on Windows Executables for Software Restriction Policies |For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is Enabled.For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is Not Defined.
1.9.59 	|MSS: (AutoAdminLogon) Enable Automatic Logon (not recommended) |Disabled
1.9.60 	|MSS: (DisableIPSourceRouting) IP source routing protection level (protects against packet spoofing) |For all profiles, the recommended state for this setting is Highest protection, source routing is completely disabled.
1.9.61 	|MSS: (EnableICMPRedirect) Allow ICMP redirects to override OSPF generated routes |Disabled
1.9.62 	|MSS: (KeepAliveTime) How often keep-alive packets are sent in milliseconds |For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is 5 minutes.For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is Not Defined.
1.9.62 	|MSS: (KeepAliveTime) How often keep-alive packets are sent in milliseconds |For the SSLF Member Server and SSLF Domain Controller profile(s), the recommended value is 5 minutes.For the Enterprise Member Server and Enterprise Domain Controller profile(s), the recommended value is Not Defined.
1.9.63 	|MSS: (NoDefaultExempt) Configure IPSec exemptions for various types of network traffic |For all profiles, the recommended state for this setting is Only ISAKMP is exempt (recommended for Windows Server 2003).
1.9.64 	|MSS: (NoNameReleaseOnDemand) Allow the computer to ignore NetBIOS name release requests except from WINS servers |Enabled
1.9.65 	|MSS: (NtfsDisable8dot3NameCreation) Enable the computer to stop generating 8.3 style filenames (recommended) |Enabled
1.9.66 	|MSS: (PerformRouterDiscovery) Allow IRDP to detect and configure Default Gateway addresses (could lead to DoS) |Disabled
1.9.67 	|MSS: (SafeDllSearchMode) Enable Safe DLL search mode (recommended) |Enabled
1.9.68 	|MSS: (ScreenSaverGracePeriod) The time in seconds before the screen saver grace period expires (0 recommended) |0
1.9.69 	|MSS: (TCPMaxDataRetransmissions) How many times unacknowledged data is retransmitted (3 recommended, 5 is default) |3
1.9.70 	|MSS: (WarningLevel) Percentage threshold for the security event log at which the system will generate a warning 	90% or less
1.9.71 	|MSS: (DisableIPSourceRouting IPv6) IP source routing protection level (protects against packet spoofing) |For all profiles, the recommended state for this setting is Highest protection, source routing is completely disabled.
1.9.72 	|MSS: (TCPMaxDataRetransmissions) IPv6 How many times unacknowledged data is retransmitted (3 recommended, 5 is default) |3

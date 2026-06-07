# Windows Troubleshooting

## 1. Common Command-Line Tools
Here are the essential commands used to fix corrupted system files:

- 'sfc /scannow' - Scans and repairs corrupted windows system files.
- 'chkdsk /f /r' - Check the hard drive for file system errors and bad sectors.
-  'DISM /Online /Cleanup-Image /RestoreHealth' - Repairs the windows system image using Windows Update.

## 2. Active Directory Issues
- Notes on resolving domain join errors:
- the client machine's DNS server must point directly to the Domain Controller IP.
- Time synchronization between the client and the DC using 'net time \\domaincontroller /set /y".

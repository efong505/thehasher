# thehasher
## AUTHOR
	Edward Fong (edwardfongabq@gmail.com)

## SYNOPSIS
    The Hasher GUI allows the user to check files against file hashes.

## DESCRIPTION 
    The Hasher is a GUI based on PowerShell that allow the user to add a hash string to a textbox field. A file open button opens a file explorer
	to choose the file that you want to run the hash against. The application uses the PowerSWhell Get-FileHash commandlet to run get the hash of the file. You can also choose the encryption algorithm via a ComboBox Dropdown. The encryption choices are SHA1, SHA256, SHA384, SHA512, and MD5. ONce both choices are set, clicking the Check Hash button will display the result, whether or not the hash mathces. 

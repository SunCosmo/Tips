# Using Vim in Powershell

## Operating System: 

    Windows10 64bit

## Powershell Version: 
```powershell
PS > $PSVersionTable

Name                           Value
----                           -----
PSVersion                      6.1.0
PSEdition                      Core
GitCommitId                    6.1.0
OS                             Microsoft Windows 6.1.7601 S
Platform                       Win32NT
PSCompatibleVersions           {1.0, 2.0, 3.0, 4.0...}
PSRemotingProtocolVersion      2.3
SerializationVersion           1.1.0.1
WSManStackVersion              3.0
```

## Vim Version:

    VIM - Vi IMproved 8.0 (2016 Sep 12, compiled Apr 23 2017 19:48:19)

## Steps:

1\) Download and install vim on Windows.

2\) Edit vimrc in vim install dir:
```lisp
    set encoding=utf-8
    set termencoding=utf-8
    set fileencoding=utf-8
    set fileencodings=ucs-bom,utf-8,chinese,cp936
```




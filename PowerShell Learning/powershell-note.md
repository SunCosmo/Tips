PowerShell MS 官方文档: https://docs.microsoft.com/zh-cn/powershell/

PowerShell 中文博客: https://www.pstips.net/

# Cmdlet 使用谓词-名词的名称来减少命令记忆

PowerShell 使用“谓词 - 名词”命名系统:

Get-Command -Verb [name] <==> 查找谓词名为'name'的cmdlet

Get-Command -Noun [name] <==> 查找名词名为'name'的cmdlet

# Cmdlet 使用标准参数

PowerShell建议但不会保证每个 cmdlet 都符合标准

PowerShell 还标准化参数分隔符. 使用 PowerShell 命令,参数名称前面始终带有"-".

在任何 cmdlet 上指定 -? 参数时, PowerShell 将显示该 cmdlet 的帮助. 未执行此 cmdle.

//TODO 收集通用参数的用途

PowerShell 有几个通用参数. 这些参数由 PowerShell 引擎控制。 通用参数的行为方式始终相同。 通用参数有 
WhatIf、
Confirm、
Verbose、
Debug、
Warn、
ErrorAction、
ErrorVariable、
OutVariable、
OutBuffer


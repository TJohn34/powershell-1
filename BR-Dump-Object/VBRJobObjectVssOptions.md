# VBRJobObjectVssOptions [Veeam.Backup.Model.CGuestProcessingOptions]
``` powershell
$job = @(Get-VBRJob | where { $_.JobType -eq "Backup" })[0]
$JobObject = @(Get-VBRJobObject -job $Job)[0]
$VBRJobObjectVssOptions = Get-VBRJobObjectVssOptions -ObjectInJob $JobObject
```
* $VBRJobObjectVssOptions.ApplyAppProcOptions()  Def [void ApplyAppProcOptions(Veeam.Backup.Model.CVssSnapshotOptions vssSnapshotOptions, Veeam.Backup.Model.CSqlBackupOptions sqlBackupOptions, Veeam.Backup.Model.COracleBackupOptions oracleBackupOptions, Veeam.Backup.Model.CExchangeBackupOptions exchangeBackupOptions, Veeam.Backup.Model.CGuestScriptsOptions scriptsOptions, Veeam.Backup.Model.CGuestFSExcludeOptions guestFSExcludeOptions), void ApplyAppProcOptions(Veeam.Backup.Model.CVssSnapshotOptions vssSnapshotOptions, Veeam.Backup.Model.CSqlBackupOptions sqlBackupOptions, Veeam.Backup.Model.CExchangeBackupOptions exchangeBackupOptions), void ApplyAppProcOptions(Veeam.Backup.Model.CVssSnapshotOptions vssSnapshotOptions), void ApplyAppProcOptions(Veeam.Backup.Model.CVssSnapshotOptions vssSnapshotOptions, Veeam.Backup.Model.CSqlBackupOptions sqlBackupOptions), void ApplyAppProcOptions(Veeam.Backup.Model.CVssSnapshotOptions vssSnapshotOptions, Veeam.Backup.Model.COracleBackupOptions oracleBackupOptions), void ApplyAppProcOptions(Veeam.Backup.Model.CVssSnapshotOptions vssSnapshotOptions, Veeam.Backup.Model.CExchangeBackupOptions exchangeBackupOptions), void ApplyAppProcOptions(Veeam.Backup.Model.CVssSnapshotOptions vssSnapshotOptions, Veeam.Backup.Model.CGuestScriptsOptions scriptsOptions), void ApplyAppProcOptions(Veeam.Backup.Model.CVssSnapshotOptions vssSnapshotOptions, Veeam.Backup.Model.CGuestFSExcludeOptions guestFSExcludeOptions)]
* $VBRJobObjectVssOptions.ApplyCreds()  Def [void ApplyCreds(guid winCredsId, guid linCredsId)]
* $VBRJobObjectVssOptions.ApplyGuestFSIndexingOptions()  Def [void ApplyGuestFSIndexingOptions(Veeam.Backup.Model.CGuestFSIndexingOptions winGuestFSIndexingOptions, Veeam.Backup.Model.CGuestFSIndexingOptions linGuestFSIndexingOptions)]
* $VBRJobObjectVssOptions.Clone()  Def [Veeam.Backup.Model.CGuestProcessingOptions Clone(), Veeam.Backup.Model.CGuestProcessingOptions ICloneable[CGuestProcessingOptions].Clone(), System.Object ICloneable.Clone()]
* $VBRJobObjectVssOptions.IsBackupOracleRequired()  Def [bool IsBackupOracleRequired()]
* $VBRJobObjectVssOptions.IsBackupSqlRequired()  Def [bool IsBackupSqlRequired()]
* $VBRJobObjectVssOptions.IsDontTruncateEnabled()  Def [bool IsDontTruncateEnabled()]
* $VBRJobObjectVssOptions.IsGuestFsExcludeOptionsRequired()  Def [bool IsGuestFsExcludeOptionsRequired()]
* $VBRJobObjectVssOptions.IsIndexingRequired()  Def [bool IsIndexingRequired()]
* $VBRJobObjectVssOptions.IsLinIndexingRequired()  Def [bool IsLinIndexingRequired()]
* $VBRJobObjectVssOptions.IsScriptingAllowed()  Def [bool IsScriptingAllowed()]
* $VBRJobObjectVssOptions.IsScriptingTurnedOn()  Def [bool IsScriptingTurnedOn()]
* $VBRJobObjectVssOptions.IsTransactionLogsProcessingAllowed()  Def [bool IsTransactionLogsProcessingAllowed()]
* $VBRJobObjectVssOptions.IsTruncateSqlAllowed()  Def [bool IsTruncateSqlAllowed()]
* $VBRJobObjectVssOptions.IsWinIndexingRequired()  Def [bool IsWinIndexingRequired()]
* $VBRJobObjectVssOptions.ResetLinCreds()  Def [void ResetLinCreds()]
* $VBRJobObjectVssOptions.ResetWinCreds()  Def [void ResetWinCreds()]
* $VBRJobObjectVssOptions.Serial()  Def [void Serial(System.Xml.XmlNode node)]
* $VBRJobObjectVssOptions.Serialize()  Def [string Serialize()]
* $VBRJobObjectVssOptions.SetScriptingAllowed()  Def [void SetScriptingAllowed()]
* $VBRJobObjectVssOptions.SetTransactionLogsProcessingAllowed()  Def [void SetTransactionLogsProcessingAllowed()]
* $VBRJobObjectVssOptions.AreLinCredsSet \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.AreWinCredsSet \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.Enabled \[System.Boolean\]
* $VBRJobObjectVssOptions.ExchangeBackupOptions \[Veeam.Backup.Model.CExchangeBackupOptions\]
* $VBRJobObjectVssOptions.ExchangeBackupOptions.Apply()  Def [void Apply(Veeam.Backup.Model.CExchangeBackupOptions options)]
* $VBRJobObjectVssOptions.ExchangeBackupOptions.TransactionLogsProcessing \[Veeam.Backup.Model.ETransactionLogsProcessing\]
* $VBRJobObjectVssOptions.ExchangeBackupOptions.TransactionLogsProcessing.value__ \[System.Int32\]
* $VBRJobObjectVssOptions.ExcludedIndexingFolders \[System.String[]\]
* $VBRJobObjectVssOptions.GuestFSExcludeOptions \[Veeam.Backup.Model.CGuestFSExcludeOptions\]
* $VBRJobObjectVssOptions.GuestFSExcludeOptions.Apply()  Def [void Apply(Veeam.Backup.Model.CGuestFSExcludeOptions options)]
* $VBRJobObjectVssOptions.GuestFSExcludeOptions.BackupScope \[Veeam.Backup.Model.EGuestFSBackupScope\] \($null\)
* $VBRJobObjectVssOptions.GuestFSExcludeOptions.ExcludeList \[System.String[]\] \($null\)
* $VBRJobObjectVssOptions.GuestFSExcludeOptions.FileExcludeEnabled \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.GuestFSExcludeOptions.IncludeList \[System.String[]\] \($null\)
* $VBRJobObjectVssOptions.GuestFSIndexingType \[Veeam.Backup.Model.EGuestFSIndexingType\]
* $VBRJobObjectVssOptions.GuestFSIndexingType.value__ \[System.Int32\]
* $VBRJobObjectVssOptions.GuestProxyAutoDetect \[System.Boolean\]
* $VBRJobObjectVssOptions.GuestScriptsOptions \[Veeam.Backup.Model.CGuestScriptsOptions\]
* $VBRJobObjectVssOptions.GuestScriptsOptions.Apply()  Def [void Apply(Veeam.Backup.Model.CGuestScriptsOptions options)]
* $VBRJobObjectVssOptions.GuestScriptsOptions.IsAtLeastOneScriptSet \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.GuestScriptsOptions.LinScriptFiles \[Veeam.Backup.Model.CScriptFiles\]
* $VBRJobObjectVssOptions.GuestScriptsOptions.LinScriptFiles.SetInXmlNode()  Def [void SetInXmlNode(System.Xml.XmlNode parentNode, string nodeName)]
* $VBRJobObjectVssOptions.GuestScriptsOptions.LinScriptFiles.IsAtLeastOneScriptSet \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.GuestScriptsOptions.LinScriptFiles.PostScriptFilePath \[System.String\] \($null\)
* $VBRJobObjectVssOptions.GuestScriptsOptions.LinScriptFiles.PreScriptFilePath \[System.String\] \($null\)
* $VBRJobObjectVssOptions.GuestScriptsOptions.ScriptingMode \[Veeam.Backup.Model.EScriptingMode\] \($null\)
* $VBRJobObjectVssOptions.GuestScriptsOptions.WinScriptFiles \[Veeam.Backup.Model.CScriptFiles\]
* $VBRJobObjectVssOptions.GuestScriptsOptions.WinScriptFiles.SetInXmlNode()  Def [void SetInXmlNode(System.Xml.XmlNode parentNode, string nodeName)]
* $VBRJobObjectVssOptions.GuestScriptsOptions.WinScriptFiles.IsAtLeastOneScriptSet \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.GuestScriptsOptions.WinScriptFiles.PostScriptFilePath \[System.String\] \($null\)
* $VBRJobObjectVssOptions.GuestScriptsOptions.WinScriptFiles.PreScriptFilePath \[System.String\] \($null\)
* $VBRJobObjectVssOptions.IgnoreErrors \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.IncludedIndexingFolders \[System.String[]\] \($null\)
* $VBRJobObjectVssOptions.IsFirstUsage \[System.Boolean\]
* $VBRJobObjectVssOptions.LinCredsId \[System.Guid\]
* $VBRJobObjectVssOptions.LinExcludedIndexingFolders \[System.String[]\]
* $VBRJobObjectVssOptions.LinGuestFSIndexingOptions \[Veeam.Backup.Model.CGuestFSIndexingOptions\]
* $VBRJobObjectVssOptions.LinGuestFSIndexingOptions.Apply()  Def [void Apply(Veeam.Backup.Model.CGuestFSIndexingOptions options)]
* $VBRJobObjectVssOptions.LinGuestFSIndexingOptions.ExcludedFolders \[System.String[]\]
* $VBRJobObjectVssOptions.LinGuestFSIndexingOptions.IncludedFolders \[System.String[]\] \($null\)
* $VBRJobObjectVssOptions.LinGuestFSIndexingOptions.IsIndexingRequired \[System.Boolean\]
* $VBRJobObjectVssOptions.LinGuestFSIndexingOptions.Type \[Veeam.Backup.Model.EGuestFSIndexingType\]
* $VBRJobObjectVssOptions.LinGuestFSIndexingOptions.Type.value__ \[System.Int32\]
* $VBRJobObjectVssOptions.LinGuestFSIndexingType \[Veeam.Backup.Model.EGuestFSIndexingType\]
* $VBRJobObjectVssOptions.LinGuestFSIndexingType.value__ \[System.Int32\]
* $VBRJobObjectVssOptions.LinIncludedIndexingFolders \[System.String[]\] \($null\)
* $VBRJobObjectVssOptions.m_isFirstUsage \[System.Boolean\]
* $VBRJobObjectVssOptions.OracleBackupOptions \[Veeam.Backup.Model.COracleBackupOptions\]
* $VBRJobObjectVssOptions.OracleBackupOptions.Apply()  Def [void Apply(Veeam.Backup.Model.COracleBackupOptions options)]
* $VBRJobObjectVssOptions.OracleBackupOptions.ArchivedLogsMaxAgeHours \[System.Int32\]
* $VBRJobObjectVssOptions.OracleBackupOptions.ArchivedLogsMaxSizeMb \[System.Int32\]
* $VBRJobObjectVssOptions.OracleBackupOptions.ArchivedLogsTruncation \[Veeam.Backup.Model.EArchivedLogsTruncation\] \($null\)
* $VBRJobObjectVssOptions.OracleBackupOptions.BackupLogsEnabled \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.OracleBackupOptions.BackupLogsFrequencyMin \[System.Int32\]
* $VBRJobObjectVssOptions.OracleBackupOptions.ProxyAutoSelect \[System.Boolean\]
* $VBRJobObjectVssOptions.OracleBackupOptions.RetainDays \[System.Int32\]
* $VBRJobObjectVssOptions.OracleBackupOptions.SysdbaCredsId \[System.Guid\]
* $VBRJobObjectVssOptions.OracleBackupOptions.TransactionLogsProcessing \[Veeam.Backup.Model.ETransactionLogsProcessing\] \($null\)
* $VBRJobObjectVssOptions.OracleBackupOptions.UseDbBackupRetention \[System.Boolean\]
* $VBRJobObjectVssOptions.SqlBackupOptions \[Veeam.Backup.Model.CSqlBackupOptions\]
* $VBRJobObjectVssOptions.SqlBackupOptions.Apply()  Def [void Apply(Veeam.Backup.Model.CSqlBackupOptions options)]
* $VBRJobObjectVssOptions.SqlBackupOptions.BackupLogsEnabled \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.SqlBackupOptions.BackupLogsFrequencyMin \[System.Int32\]
* $VBRJobObjectVssOptions.SqlBackupOptions.NeverTruncateLogs \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.SqlBackupOptions.ProxyAutoSelect \[System.Boolean\]
* $VBRJobObjectVssOptions.SqlBackupOptions.RetainDays \[System.Int32\]
* $VBRJobObjectVssOptions.SqlBackupOptions.TransactionLogsProcessing \[Veeam.Backup.Model.ETransactionLogsProcessing\]
* $VBRJobObjectVssOptions.SqlBackupOptions.TransactionLogsProcessing.value__ \[System.Int32\]
* $VBRJobObjectVssOptions.SqlBackupOptions.UseDbBackupRetention \[System.Boolean\]
* $VBRJobObjectVssOptions.VssSnapshotOptions \[Veeam.Backup.Model.CVssSnapshotOptions\]
* $VBRJobObjectVssOptions.VssSnapshotOptions.Apply()  Def [void Apply(Veeam.Backup.Model.CVssSnapshotOptions options)]
* $VBRJobObjectVssOptions.VssSnapshotOptions.Enabled \[System.Boolean\]
* $VBRJobObjectVssOptions.VssSnapshotOptions.IgnoreErrors \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.VssSnapshotOptions.IsCopyOnly \[System.Boolean\] \($null\)
* $VBRJobObjectVssOptions.WinCredsId \[System.Guid\]
* $VBRJobObjectVssOptions.WinGuestFSIndexingOptions \[Veeam.Backup.Model.CGuestFSIndexingOptions\]
* $VBRJobObjectVssOptions.WinGuestFSIndexingOptions.Apply()  Def [void Apply(Veeam.Backup.Model.CGuestFSIndexingOptions options)]
* $VBRJobObjectVssOptions.WinGuestFSIndexingOptions.ExcludedFolders \[System.String[]\]
* $VBRJobObjectVssOptions.WinGuestFSIndexingOptions.IncludedFolders \[System.String[]\] \($null\)
* $VBRJobObjectVssOptions.WinGuestFSIndexingOptions.IsIndexingRequired \[System.Boolean\]
* $VBRJobObjectVssOptions.WinGuestFSIndexingOptions.Type \[Veeam.Backup.Model.EGuestFSIndexingType\]
* $VBRJobObjectVssOptions.WinGuestFSIndexingOptions.Type.value__ \[System.Int32\]




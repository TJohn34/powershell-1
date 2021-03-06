# VBRBackupStorage [Veeam.Backup.Core.CStorage]
``` powershell
$VBRBackup = @(Get-VBRBackup)[0]
$VBRBackupStorage = @($VBRBackup.GetAllStorages())[0]
```
* $VBRBackupStorage.BeginTransaction()  Def [Veeam.Backup.Common.CTransaction BeginTransaction()]
* $VBRBackupStorage.CheckVersion()  Def [void CheckVersion()]
* $VBRBackupStorage.Delete()  Def [void Delete()]
* $VBRBackupStorage.DeleteCryptoKeys()  Def [void DeleteCryptoKeys()]
* $VBRBackupStorage.DeleteNoThrow()  Def [void DeleteNoThrow()]
* $VBRBackupStorage.FindBackup()  Def [Veeam.Backup.Core.CBackup FindBackup()]
* $VBRBackupStorage.FindHost()  Def [Veeam.Backup.Core.Common.CHost FindHost()]
* $VBRBackupStorage.FindJob()  Def [Veeam.Backup.Core.CBackupJob FindJob()]
* $VBRBackupStorage.FindMetaCryptoKey()  Def [Veeam.Backup.Core.CCryptoKey FindMetaCryptoKey()]
* $VBRBackupStorage.FindNextByLink()  Def [Veeam.Backup.Core.CStorage FindNextByLink()]
* $VBRBackupStorage.FindNextObjectByLink()  Def [Veeam.Backup.Core.ILinkableObject FindNextObjectByLink(), Veeam.Backup.Core.ILinkableObject ILinkableObject.FindNextObjectByLink()]
* $VBRBackupStorage.FindOibForObject()  Def [Veeam.Backup.Core.COib FindOibForObject(guid objId)]
* $VBRBackupStorage.FindPreviousObjectByLink()  Def [System.Collections.Generic.IEnumerable[Veeam.Backup.Core.ILinkableObject] FindPreviousObjectByLink(), System.Collections.Generic.IEnumerable[Veeam.Backup.Core.ILinkableObject] ILinkableObject.FindPreviousObjectByLink()]
* $VBRBackupStorage.FindStorageCryptoKey()  Def [Veeam.Backup.Core.CCryptoKey FindStorageCryptoKey()]
* $VBRBackupStorage.GetBackup()  Def [Veeam.Backup.Core.CBackup GetBackup()]
* $VBRBackupStorage.GetDbOracleOibs()  Def [System.Collections.Generic.IEnumerable[Veeam.Backup.Core.CDbOracleOib] GetDbOracleOibs()]
* $VBRBackupStorage.GetDbSqlOibs()  Def [System.Collections.Generic.IEnumerable[Veeam.Backup.Core.CDbSqlOib] GetDbSqlOibs()]
* $VBRBackupStorage.GetDirPath()  Def [Veeam.Backup.Common.CLegacyPath GetDirPath(Veeam.Backup.Common.IPathCommander fileCommander)]
* $VBRBackupStorage.GetEncryptedDbOracleOibs()  Def [System.Collections.Generic.IEnumerable[Veeam.Backup.Model.COracleOibEncryptedInfo] GetEncryptedDbOracleOibs()]
* $VBRBackupStorage.GetEncryptedDbSqlOibs()  Def [System.Collections.Generic.IEnumerable[Veeam.Backup.Model.CDbSqlOibEncryptedInfo] GetEncryptedDbSqlOibs()]
* $VBRBackupStorage.GetFileName()  Def [Veeam.Backup.Common.CLegacyPath GetFileName(Veeam.Backup.Common.IPathCommander fileCommander), Veeam.Backup.Common.CLegacyPath GetFileName(Veeam.Backup.Core.IStorageCommander storageCommander)]
* $VBRBackupStorage.GetHost()  Def [Veeam.Backup.Core.Common.CHost GetHost()]
* $VBRBackupStorage.GetOibs()  Def [System.Collections.Generic.IEnumerable[Veeam.Backup.Core.COib] GetOibs(), System.Collections.Generic.IEnumerable[Veeam.Backup.Core.COib] IOibContainer.GetOibs()]
* $VBRBackupStorage.GetSortedOibs()  Def [System.Collections.Generic.IEnumerable[Veeam.Backup.Core.COib] GetSortedOibs()]
* $VBRBackupStorage.GetStoragesChain()  Def [Veeam.Backup.Core.CStorage[] GetStoragesChain()]
* $VBRBackupStorage.GetStorageType()  Def [Veeam.Backup.Model.CStorageInfo+EType GetStorageType(), Veeam.Backup.Model.CStorageInfo+EType IStorageSortable.GetStorageType()]
* $VBRBackupStorage.IsEmpty()  Def [bool IsEmpty(), bool IReadOnlyGfsInfo.IsEmpty()]
* $VBRBackupStorage.IsTemp()  Def [bool IsTemp()]
* $VBRBackupStorage.IsVbk()  Def [bool IsVbk()]
* $VBRBackupStorage.IsVib()  Def [bool IsVib()]
* $VBRBackupStorage.IsVlb()  Def [bool IsVlb()]
* $VBRBackupStorage.IsVrb()  Def [bool IsVrb()]
* $VBRBackupStorage.IsVsb()  Def [bool IsVsb()]
* $VBRBackupStorage.SetAvailability()  Def [void SetAvailability(Veeam.Backup.Model.CStorageInfo+EStorageAvailabilityState availability)]
* $VBRBackupStorage.SetCachedBackup()  Def [void SetCachedBackup(Veeam.Backup.Core.CBackup cachedBackup)]
* $VBRBackupStorage.SetLastCompactTime()  Def [void SetLastCompactTime(System.Nullable[datetime] dateTime)]
* $VBRBackupStorage.SetLastRecheckTimeIfNewer()  Def [void SetLastRecheckTimeIfNewer(System.Nullable[datetime] dateTime)]
* $VBRBackupStorage.SetLinkId()  Def [void SetLinkId(System.Nullable[guid] linkId), void IStorage.SetLinkId(System.Nullable[guid] linkId), void ILinkableObject.SetLinkId(System.Nullable[guid] linkId)]
* $VBRBackupStorage.SetModificationTime()  Def [void SetModificationTime(datetime dateTime)]
* $VBRBackupStorage.SetStats()  Def [void SetStats(Veeam.Backup.Model.CBackupStats stats)]
* $VBRBackupStorage.Update()  Def [void Update(Veeam.Backup.Model.CStorageInfo info), void Update(), void Update(datetime creationTime, Veeam.Backup.Common.EKbBlockSize blockSize, Veeam.Backup.Model.CBackupStats stats), void Update(datetime creationTime), void Update(guid hostId, Veeam.Backup.Common.CLegacyPath filePath), void IStorage.Update()]
* $VBRBackupStorage.ActualEndDate \[$null\] \($null\)
* $VBRBackupStorage.BackupId \[System.Guid\]
* $VBRBackupStorage.BlockAlignmentSize \[System.Int32\]
* $VBRBackupStorage.BlockSize \[Veeam.Backup.Common.EKbBlockSize\]
* $VBRBackupStorage.BlockSize.value__ \[System.Int32\]
* $VBRBackupStorage.CreationMode \[Veeam.Backup.Model.CStorageInfo+ECreationMode\] \($null\)
* $VBRBackupStorage.CreationTime \[System.DateTime\]
* $VBRBackupStorage.CreationTimeUtc \[System.DateTime\]
* $VBRBackupStorage.FilePath \[Veeam.Backup.Common.CLegacyPath\]
* $VBRBackupStorage.FilePath.AddDelimiterIfNeeded()  Def [Veeam.Backup.Common.CLegacyPath AddDelimiterIfNeeded(string delimiter)]
* $VBRBackupStorage.FilePath.GetSchema()  Def [System.Xml.Schema.XmlSchema GetSchema(), System.Xml.Schema.XmlSchema IXmlSerializable.GetSchema()]
* $VBRBackupStorage.FilePath.ReadXml()  Def [void ReadXml(System.Xml.XmlReader reader), void IXmlSerializable.ReadXml(System.Xml.XmlReader reader)]
* $VBRBackupStorage.FilePath.Trim()  Def [Veeam.Backup.Common.CLegacyPath Trim()]
* $VBRBackupStorage.FilePath.TrimDelimiter()  Def [Veeam.Backup.Common.CLegacyPath TrimDelimiter(char delimiter)]
* $VBRBackupStorage.FilePath.WriteXml()  Def [void WriteXml(System.Xml.XmlWriter writer), void IXmlSerializable.WriteXml(System.Xml.XmlWriter writer)]
* $VBRBackupStorage.FilePath.IsVbm \[System.Boolean\] \($null\)
* $VBRBackupStorage.GfsPeriod \[Veeam.Backup.Model.CStorageInfo+EStorageGFSPeriod\] \($null\)
* $VBRBackupStorage.HasVbk \[System.Boolean\] \($null\)
* $VBRBackupStorage.HostId \[System.Guid\]
* $VBRBackupStorage.Id \[System.Guid\]
* $VBRBackupStorage.Info \[Veeam.Backup.Model.CStorageInfo\]
* $VBRBackupStorage.Info.Clone()  Def [Veeam.Backup.Model.CStorageInfo Clone()]
* $VBRBackupStorage.Info.GetStorageType()  Def [Veeam.Backup.Model.CStorageInfo+EType GetStorageType(), Veeam.Backup.Model.CStorageInfo+EType IStorageInfo.GetStorageType()]
* $VBRBackupStorage.Info.SetAvailability()  Def [void SetAvailability(Veeam.Backup.Model.CStorageInfo+EStorageAvailabilityState availability)]
* $VBRBackupStorage.Info.Availability \[Veeam.Backup.Model.CStorageInfo+EStorageAvailabilityState\] \($null\)
* $VBRBackupStorage.Info.BackupId \[System.Guid\]
* $VBRBackupStorage.Info.BlockAlignmentSize \[System.Int32\]
* $VBRBackupStorage.Info.BlockSize \[Veeam.Backup.Common.EKbBlockSize\]
* $VBRBackupStorage.Info.BlockSize.value__ \[System.Int32\]
* $VBRBackupStorage.Info.CreationMode \[Veeam.Backup.Model.CStorageInfo+ECreationMode\] \($null\)
* $VBRBackupStorage.Info.CreationTime \[System.DateTime\]
* $VBRBackupStorage.Info.CreationTimeUtc \[System.DateTime\]
* $VBRBackupStorage.Info.FilePath \[Veeam.Backup.Common.CLegacyPath\]
* $VBRBackupStorage.Info.FilePath.AddDelimiterIfNeeded()  Def [Veeam.Backup.Common.CLegacyPath AddDelimiterIfNeeded(string delimiter)]
* $VBRBackupStorage.Info.FilePath.GetSchema()  Def [System.Xml.Schema.XmlSchema GetSchema(), System.Xml.Schema.XmlSchema IXmlSerializable.GetSchema()]
* $VBRBackupStorage.Info.FilePath.ReadXml()  Def [void ReadXml(System.Xml.XmlReader reader), void IXmlSerializable.ReadXml(System.Xml.XmlReader reader)]
* $VBRBackupStorage.Info.FilePath.Trim()  Def [Veeam.Backup.Common.CLegacyPath Trim()]
* $VBRBackupStorage.Info.FilePath.TrimDelimiter()  Def [Veeam.Backup.Common.CLegacyPath TrimDelimiter(char delimiter)]
* $VBRBackupStorage.Info.FilePath.WriteXml()  Def [void WriteXml(System.Xml.XmlWriter writer), void IXmlSerializable.WriteXml(System.Xml.XmlWriter writer)]
* $VBRBackupStorage.Info.FilePath.IsVbm \[System.Boolean\] \($null\)
* $VBRBackupStorage.Info.GfsPeriod \[Veeam.Backup.Model.CStorageInfo+EStorageGFSPeriod\] \($null\)
* $VBRBackupStorage.Info.HostId \[System.Guid\]
* $VBRBackupStorage.Info.Id \[System.Guid\]
* $VBRBackupStorage.Info.LastCompactTime \[$null\] \($null\)
* $VBRBackupStorage.Info.LastRecheckTime \[$null\] \($null\)
* $VBRBackupStorage.Info.LinkId \[System.Guid\]
* $VBRBackupStorage.Info.MetaCryptoKeyId \[System.Guid\]
* $VBRBackupStorage.Info.ModificationTime \[System.DateTime\]
* $VBRBackupStorage.Info.ObjectId \[System.Guid\]
* $VBRBackupStorage.Info.PartialIncrement \[System.Boolean\] \($null\)
* $VBRBackupStorage.Info.PartialPath \[Veeam.Backup.Common.CPartialPath\]
* $VBRBackupStorage.Info.PartialPath.AppendToTail()  Def [Veeam.Backup.Common.CPartialPath AppendToTail(string postfix)]
* $VBRBackupStorage.Info.PartialPath.CanSubstract()  Def [bool CanSubstract(Veeam.Backup.Common.CPath partToSubstract)]
* $VBRBackupStorage.Info.PartialPath.Combine()  Def [Veeam.Backup.Common.CPartialPath Combine(Veeam.Backup.Common.CPartialPath childPath), Veeam.Backup.Common.CPartialPath Combine(Veeam.Backup.Common.CFileName fileName)]
* $VBRBackupStorage.Info.PartialPath.FilterInvalidCharacters()  Def [Veeam.Backup.Common.CPartialPath FilterInvalidCharacters(Veeam.Backup.Common.EPathCommanderType pathCommanderType)]
* $VBRBackupStorage.Info.PartialPath.GetChild()  Def [Veeam.Backup.Common.CPartialPath GetChild(Params string[] childFolderElements)]
* $VBRBackupStorage.Info.PartialPath.GetFileName()  Def [Veeam.Backup.Common.CFileName GetFileName()]
* $VBRBackupStorage.Info.PartialPath.GetParent()  Def [Veeam.Backup.Common.CPartialPath GetParent()]
* $VBRBackupStorage.Info.PartialPath.Serialize()  Def [string Serialize()]
* $VBRBackupStorage.Info.PartialPath.Substract()  Def [Veeam.Backup.Common.CPartialPath Substract(Veeam.Backup.Common.CPartialPath partToSubstract)]
* $VBRBackupStorage.Info.PartialPath.Elements \[System.String[]\]
* $VBRBackupStorage.Info.PartialPath.Internal \[Veeam.Backup.Common.CPath\]
* $VBRBackupStorage.Info.PartialPath.Internal.AppendToTail()  Def [Veeam.Backup.Common.CPath AppendToTail(string postfix)]
* $VBRBackupStorage.Info.PartialPath.Internal.CanSubstract()  Def [bool CanSubstract(Veeam.Backup.Common.CPath partToSubstract)]
* $VBRBackupStorage.Info.PartialPath.Internal.Combine()  Def [Veeam.Backup.Common.CPath Combine(Veeam.Backup.Common.CFileName fileName), Veeam.Backup.Common.CPath Combine(Veeam.Backup.Common.CPath childPath)]
* $VBRBackupStorage.Info.PartialPath.Internal.FilterInvalidCharacters()  Def [Veeam.Backup.Common.CPath FilterInvalidCharacters(Veeam.Backup.Common.EPathCommanderType pathCommanderType)]
* $VBRBackupStorage.Info.PartialPath.Internal.GetAsString()  Def [string GetAsString(Veeam.Backup.Common.IPathCommander pathCommander)]
* $VBRBackupStorage.Info.PartialPath.Internal.GetChild()  Def [Veeam.Backup.Common.CPath GetChild(Params string[] childFolderElements)]
* $VBRBackupStorage.Info.PartialPath.Internal.GetFileName()  Def [Veeam.Backup.Common.CFileName GetFileName()]
* $VBRBackupStorage.Info.PartialPath.Internal.GetParent()  Def [Veeam.Backup.Common.CPath GetParent()]
* $VBRBackupStorage.Info.PartialPath.Internal.Serialize()  Def [string Serialize()]
* $VBRBackupStorage.Info.PartialPath.Internal.Substract()  Def [Veeam.Backup.Common.CPath Substract(Veeam.Backup.Common.CPath partToSubstract)]
* $VBRBackupStorage.Info.PartialPath.Internal.Elements \[System.String[]\]
* $VBRBackupStorage.Info.PartialPath.Internal.IsEmpty \[System.Boolean\] \($null\)
* $VBRBackupStorage.Info.PartialPath.Internal.IsFilePath \[System.Boolean\]
* $VBRBackupStorage.Info.PartialPath.Internal.IsRelative \[System.Boolean\]
* $VBRBackupStorage.Info.PartialPath.Internal.Root \[$null\] \($null\)
* $VBRBackupStorage.Info.PartialPath.IsEmpty \[System.Boolean\] \($null\)
* $VBRBackupStorage.Info.Stats \[Veeam.Backup.Model.CBackupStats\]
* $VBRBackupStorage.Info.Stats.FromXmlData()  Def [Veeam.Backup.Model.CBackupStats FromXmlData(Veeam.Backup.Common.COutputXmlData data)]
* $VBRBackupStorage.Info.Stats.GetCompressX()  Def [double GetCompressX()]
* $VBRBackupStorage.Info.Stats.GetDedupeX()  Def [double GetDedupeX()]
* $VBRBackupStorage.Info.Stats.SetData()  Def [void SetData(long backupSize, long dataSize, int dedupRatio, int compressRatio)]
* $VBRBackupStorage.Info.Stats.BackupSize \[System.Int64\]
* $VBRBackupStorage.Info.Stats.CompressRatio \[System.Int32\]
* $VBRBackupStorage.Info.Stats.DataSize \[System.Int64\]
* $VBRBackupStorage.Info.Stats.DedupRatio \[System.Int32\]
* $VBRBackupStorage.Info.StorageCryptoKeyId \[System.Guid\]
* $VBRBackupStorage.Info.TemporaryPath \[$null\] \($null\)
* $VBRBackupStorage.Info.Version \[System.Int32\]
* $VBRBackupStorage.IsAvailable \[System.Boolean\]
* $VBRBackupStorage.IsBlockAlignmentSizeSet \[System.Boolean\]
* $VBRBackupStorage.IsEncrypted \[System.Boolean\] \($null\)
* $VBRBackupStorage.IsFull \[System.Boolean\] \($null\)
* $VBRBackupStorage.IsFullFast \[System.Boolean\] \($null\)
* $VBRBackupStorage.LastCompactTime \[$null\] \($null\)
* $VBRBackupStorage.LastRecheckTime \[$null\] \($null\)
* $VBRBackupStorage.LinkableType \[Veeam.Backup.Core.LinkableObjectType\] \($null\)
* $VBRBackupStorage.LinkId \[System.Guid\]
* $VBRBackupStorage.LinkIdNullable \[System.Guid\]
* $VBRBackupStorage.MetaCryptoKeyId \[System.Guid\]
* $VBRBackupStorage.ObjectId \[System.Guid\]
* $VBRBackupStorage.PartialIncrement \[System.Boolean\] \($null\)
* $VBRBackupStorage.PartialPath \[Veeam.Backup.Common.CPartialPath\]
* $VBRBackupStorage.PartialPath.AppendToTail()  Def [Veeam.Backup.Common.CPartialPath AppendToTail(string postfix)]
* $VBRBackupStorage.PartialPath.CanSubstract()  Def [bool CanSubstract(Veeam.Backup.Common.CPath partToSubstract)]
* $VBRBackupStorage.PartialPath.Combine()  Def [Veeam.Backup.Common.CPartialPath Combine(Veeam.Backup.Common.CPartialPath childPath), Veeam.Backup.Common.CPartialPath Combine(Veeam.Backup.Common.CFileName fileName)]
* $VBRBackupStorage.PartialPath.FilterInvalidCharacters()  Def [Veeam.Backup.Common.CPartialPath FilterInvalidCharacters(Veeam.Backup.Common.EPathCommanderType pathCommanderType)]
* $VBRBackupStorage.PartialPath.GetChild()  Def [Veeam.Backup.Common.CPartialPath GetChild(Params string[] childFolderElements)]
* $VBRBackupStorage.PartialPath.GetFileName()  Def [Veeam.Backup.Common.CFileName GetFileName()]
* $VBRBackupStorage.PartialPath.GetParent()  Def [Veeam.Backup.Common.CPartialPath GetParent()]
* $VBRBackupStorage.PartialPath.Serialize()  Def [string Serialize()]
* $VBRBackupStorage.PartialPath.Substract()  Def [Veeam.Backup.Common.CPartialPath Substract(Veeam.Backup.Common.CPartialPath partToSubstract)]
* $VBRBackupStorage.PartialPath.Elements \[System.String[]\]
* $VBRBackupStorage.PartialPath.Internal \[Veeam.Backup.Common.CPath\]
* $VBRBackupStorage.PartialPath.Internal.AppendToTail()  Def [Veeam.Backup.Common.CPath AppendToTail(string postfix)]
* $VBRBackupStorage.PartialPath.Internal.CanSubstract()  Def [bool CanSubstract(Veeam.Backup.Common.CPath partToSubstract)]
* $VBRBackupStorage.PartialPath.Internal.Combine()  Def [Veeam.Backup.Common.CPath Combine(Veeam.Backup.Common.CFileName fileName), Veeam.Backup.Common.CPath Combine(Veeam.Backup.Common.CPath childPath)]
* $VBRBackupStorage.PartialPath.Internal.FilterInvalidCharacters()  Def [Veeam.Backup.Common.CPath FilterInvalidCharacters(Veeam.Backup.Common.EPathCommanderType pathCommanderType)]
* $VBRBackupStorage.PartialPath.Internal.GetAsString()  Def [string GetAsString(Veeam.Backup.Common.IPathCommander pathCommander)]
* $VBRBackupStorage.PartialPath.Internal.GetChild()  Def [Veeam.Backup.Common.CPath GetChild(Params string[] childFolderElements)]
* $VBRBackupStorage.PartialPath.Internal.GetFileName()  Def [Veeam.Backup.Common.CFileName GetFileName()]
* $VBRBackupStorage.PartialPath.Internal.GetParent()  Def [Veeam.Backup.Common.CPath GetParent()]
* $VBRBackupStorage.PartialPath.Internal.Serialize()  Def [string Serialize()]
* $VBRBackupStorage.PartialPath.Internal.Substract()  Def [Veeam.Backup.Common.CPath Substract(Veeam.Backup.Common.CPath partToSubstract)]
* $VBRBackupStorage.PartialPath.Internal.Elements \[System.String[]\]
* $VBRBackupStorage.PartialPath.Internal.IsEmpty \[System.Boolean\] \($null\)
* $VBRBackupStorage.PartialPath.Internal.IsFilePath \[System.Boolean\]
* $VBRBackupStorage.PartialPath.Internal.IsRelative \[System.Boolean\]
* $VBRBackupStorage.PartialPath.Internal.Root \[$null\] \($null\)
* $VBRBackupStorage.PartialPath.IsEmpty \[System.Boolean\] \($null\)
* $VBRBackupStorage.Stats \[Veeam.Backup.Model.CBackupStats\]
* $VBRBackupStorage.Stats.FromXmlData()  Def [Veeam.Backup.Model.CBackupStats FromXmlData(Veeam.Backup.Common.COutputXmlData data)]
* $VBRBackupStorage.Stats.GetCompressX()  Def [double GetCompressX()]
* $VBRBackupStorage.Stats.GetDedupeX()  Def [double GetDedupeX()]
* $VBRBackupStorage.Stats.SetData()  Def [void SetData(long backupSize, long dataSize, int dedupRatio, int compressRatio)]
* $VBRBackupStorage.Stats.BackupSize \[System.Int64\]
* $VBRBackupStorage.Stats.CompressRatio \[System.Int32\]
* $VBRBackupStorage.Stats.DataSize \[System.Int64\]
* $VBRBackupStorage.Stats.DedupRatio \[System.Int32\]
* $VBRBackupStorage.StorageCryptoKeyId \[System.Guid\]




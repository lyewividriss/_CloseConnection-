# _CloseConnection-
Func _CloseConnection()      Return $objConnection.Close EndFunc  Func _CloseRecordSet()     Return $objRecordSet.Close EndFunc  Func _CreateDatabase($varDatabaseName=0)     If $adCurrentProvider = $adProviderMSJET4 Then

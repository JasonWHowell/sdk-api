---
UID: NF:resapi.CLRES_V1_FUNCTION_TABLE
title: CLRES_V1_FUNCTION_TABLE macro (resapi.h)
description: Initializes a function table for version 1.0 of the Resource API.
helpviewer_keywords: ["CLRES_V1_FUNCTION_TABLE","CLRES_V1_FUNCTION_TABLE macro [Failover Cluster]","_wolf_clres_v1_function_table","mscs.clres_v1_function_table","resapi/CLRES_V1_FUNCTION_TABLE"]
old-location: mscs\clres_v1_function_table.htm
tech.root: MsCS
ms.assetid: 2c390cbb-3bff-4850-9496-8991c112c233
ms.date: 12/05/2018
ms.keywords: CLRES_V1_FUNCTION_TABLE, CLRES_V1_FUNCTION_TABLE macro [Failover Cluster], _wolf_clres_v1_function_table, mscs.clres_v1_function_table, resapi/CLRES_V1_FUNCTION_TABLE
req.header: resapi.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: None supported
req.target-min-winversvr: Windows Server 2008 Enterprise, Windows Server 2008 Datacenter
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - CLRES_V1_FUNCTION_TABLE
 - resapi/CLRES_V1_FUNCTION_TABLE
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - ResApi.h
api_name:
 - CLRES_V1_FUNCTION_TABLE
---

# CLRES_V1_FUNCTION_TABLE macro


## -description

Initializes a 
    function table for version 1.0 of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/resource-api">Resource API</a>.

## -parameters

### -param _Name

Label for the function table.

### -param _Version

Defines the exact version, such as <b>CLRES_VERSION_V1_00</b>.

### -param _Prefix

Prefix to be appended to the front of each of the names of the entry points in the function table.

### -param _Arbitrate

Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-parbitrate_routine">Arbitrate</a> entry point.

### -param _Release

Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-prelease_routine">Release</a> entry point.

### -param _ResControl

Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-presource_control_routine">ResourceControl</a> entry point.

### -param _ResTypeControl

Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-presource_type_control_routine">ResourceTypeControl</a> entry 
       point.

## -remarks

The <b>CLRES_V1_FUNCTION_TABLE</b> macro creates a 
     function table for version 1.0 of the 
     <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/resource-api">Resource API</a> using the version specified by the 
     <i>Version</i> parameter and the label specified by the <i>Name</i> 
     parameter. The actual names of the entry points are generated by combining the prefix specified in the 
     <i>Prefix</i> parameter with the generic names as defined in the Resource API. For example, if 
     <i>Prefix</i> is set to the string "FileShare", then the name of the 
     <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-popen_routine">Open</a> function would be "FileShareOpen". Notice 
     that the optional entry point functions may be <b>NULL</b>.

The resulting function table includes the following members.

<table>
<tr>
<th>Member</th>
<th>Description</th>
</tr>
<tr>
<td>
<i>Prefix</i>

</td>
<td>
Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-popen_routine">Open</a> entry point.

</td>
</tr>
<tr>
<td>
<i>Prefix</i>

</td>
<td>
Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-pclose_routine">Close</a> entry point.

</td>
</tr>
<tr>
<td>
<i>Prefix</i>

</td>
<td>
Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-ponline_routine">Online</a> entry point.

</td>
</tr>
<tr>
<td>
<i>Prefix</i>

</td>
<td>
Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-poffline_routine">Offline</a> entry point.

</td>
</tr>
<tr>
<td>
<i>Prefix</i>

</td>
<td>
Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-pterminate_routine">Terminate</a> entry point.

</td>
</tr>
<tr>
<td>
<i>Prefix</i>

</td>
<td>
Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-plooks_alive_routine">LooksAlive</a> entry point.

</td>
</tr>
<tr>
<td>
<i>Prefix</i>

</td>
<td>
Name of the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-pis_alive_routine">IsAlive</a> entry point.

</td>
</tr>
</table>
 

To view the format of the function table, see the 
     <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/ns-resapi-clres_function_table">CLRES_FUNCTION_TABLE</a> structure.


#### Examples

See <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/defining-structures-and-constants">Defining Structures and Constants</a> 
      in <a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/implementing-resource-dlls">Implementing Resource DLLs</a>.

<div class="code"></div>

## -see-also

<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-parbitrate_routine">Arbitrate</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/ns-resapi-clres_function_table">CLRES_FUNCTION_TABLE</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/mscs/macros">Data Structure Macros</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-prelease_routine">Release</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-presource_control_routine">ResourceControl</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/resapi/nc-resapi-presource_type_control_routine">ResourceTypeControl</a>


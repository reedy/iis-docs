﻿---
title: IPlaylistEntryInfoCollection::Count Property
TOCTitle: IPlaylistEntryInfoCollection::Count Property
ms:assetid: 440ff882-0925-48f4-a3fb-bffd7c662d29
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Dd146265(v=VS.90)
ms:contentKeyID: 19132336
ms.date: 05/02/2012
mtps_version: v=VS.90
---

# IPlaylistEntryInfoCollection::Count Property

The **Count** property gets the number of playlist entries in this collection.

    HRESULT
    Count (
       [out, retval] DWORD   *pdwEntryCount
    );

## Arguments

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>pdwEntryCount</p></td>
<td><p>A DWORD representing the number of playlist entries in this collection.</p></td>
</tr>
</tbody>
</table>


## Return Value

If the method succeeds, it returns S\_OK. If it fails, it returns an HRESULT error code.

## Notes for Implementers

Implementers are responsible for returning the correct number of entries.

## Requirements

**Header:** playlistprovider.h

**Library:** playlistprovider.dll

**Platform:** Windows Server 2008 family

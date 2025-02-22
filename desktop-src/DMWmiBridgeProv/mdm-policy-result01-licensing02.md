---
title: MDM_Policy_Result01_Licensing02 class
description: The MDM\_Policy\_Result01\_Licensing02 class represents the licensing policies available.
ms.assetid: 0f3faa78-c9ed-4166-a860-b5096b33772a
keywords:
- MDM_Policy_Result01_Licensing02 class
- MDM_Policy_Result01_Licensing02 class, described
topic_type:
- apiref
api_name:
- MDM_Policy_Result01_Licensing02
- MDM_Policy_Result01_Licensing02.InstanceID
- MDM_Policy_Result01_Licensing02.ParentID
api_location:
- Mofs\DMWmiBridgeProv.dll
api_type:
- DllExport
ms.topic: reference
ms.date: 05/31/2018
---

# MDM\_Policy\_Result01\_Licensing02 class



The **MDM\_Policy\_Result01\_Licensing02** class represents the licensing policies available.

The following syntax is simplified from MOF code and includes all inherited properties.

## Syntax

``` syntax
[InPartition("local-system"), dynamic, provider("DMWmiBridgeProv")]
class MDM_Policy_Result01_Licensing02
{
  string InstanceID;
  string ParentID;
  sint32 AllowWindowsEntitlementReactivation;
  sint32 DisallowKMSClientOnlineAVSValidation;
};
```

## Members

The **MDM\_Policy\_Result01\_Licensing02** class has these types of members:

-   [Properties](#properties)

### Properties

The **MDM\_Policy\_Result01\_Licensing02** class has these properties.

<dl> <dt>

[AllowWindowsEntitlementReactivation](/windows/client-management/mdm/policy-csp-licensing#licensing-allowwindowsentitlementreactivation)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[DisallowKMSClientOnlineAVSValidation](/windows/client-management/mdm/policy-csp-licensing#licensing-disallowkmsclientonlineavsvalidation)
</dt> <dd> <dl> <dt>

Data type: **sint32**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

**InstanceID**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**key**](/windows/desktop/WmiSdk/key-qualifier)
</dt> </dl>

Identifies the name of the parent node. For this class, the string is "Licensing".

</dd> <dt>

**ParentID**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**key**](/windows/desktop/WmiSdk/key-qualifier)
</dt> </dl>

Describes the full path to the parent node. For this class, the string is "./Vendor/MSFT/Policy/Result"

</dd> </dl>

## Requirements



| Requirement | Value |
|-------------------------------------|------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 10 \[desktop apps only\]<br/>                                                          |
| Minimum supported server<br/> | None supported<br/>                                                                            |
| Namespace<br/>                | Root\\cimv2\\mdm\\dmmap<br/>                                                                   |
| MOF<br/>                      | <dl> <dt>DMWmiBridgeProv.mof</dt> </dl>       |
| DLL<br/>                      | <dl> <dt>Mofs\\DMWmiBridgeProv.dll</dt> </dl> |



 


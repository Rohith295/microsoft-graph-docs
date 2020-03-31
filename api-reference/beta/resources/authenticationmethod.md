---
title: "authenticationMethod resource type"
description: "An authentication method registered to a user"
localization_priority: Normal
author: "mmcla"
ms.prod: "microsoft-identity-platform"
doc_type: "resourcePageType"
---

# authenticationMethod resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

An authenticationMethod resource represents an authentication method registered to a user. An [authentication method](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-authentication-methods) is something used by a user to authenticate or otherwise prove their identity to the system. Some examples include password, phone (usable via SMS or voice call), FIDO2 security keys, and more. As of this writing, password and phone methods are implemented.



## Methods

| Method       | Return Type | Description |
|:-------------|:------------|:------------|
| [List authenticationMethods](../api/authentication-list-methods.md) | [authenticationMethod](authenticationmethod.md) collection | Read properties and relationships of all of a user's authenticationMethod objects . |
| [Get authenticationMethod](../api/authenticationmethod-get.md) | [authenticationMethod](authenticationmethod.md) | Read properties and relationships of an authenticationMethod object. |

## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|id|String| Read-only.|

## Relationships

None

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.authenticationMethod",
  "baseType": "",
  "keyProperty": "id"
}-->

```json
{
  "id": "String (identifier)"
}
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "authenticationMethod resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
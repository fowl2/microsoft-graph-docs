---
title: "groupPeerOutlierRecommendationInsightSettings resource type"
description: "In the Azure AD access reviews, the groupPeerOutlierRecommendationInsightSettings represents the settings associated with group peer outlier insights, and that is used to aid reviewers to make decisions."
author: "shubhamguptacal"
ms.localizationpriority: medium
ms.prod: "governance"
doc_type: resourcePageType
---

# groupPeerOutlierRecommendationInsightSettings resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

[!INCLUDE [accessreviews-disclaimer-v2](../../includes/accessreviews-disclaimer-v2.md)]

Represents the group peer outlier insights that help reviewers make decisions for an [accessReviewScheduleDefinition](accessreviewscheduledefinition.md) object. Azure AD assesses the access that the user's peers have and provides _approve_ or _deny_ recommendation insights to the approvers.

Inherits from [accessReviewRecommendationInsightSetting](accessReviewRecommendationInsightSetting.md).

## Properties
None.


## Relationships
None.

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.groupPeerOutlierRecommendationInsightSettings",
  "baseType": "microsoft.graph.accessReviewRecommendationInsightSetting"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.groupPeerOutlierRecommendationInsightSettings"
}
```

<!--
{
  "type": "#page.annotation",
  "description": "groupPeerOutlierRecommendationInsightSettings resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": []
}
-->

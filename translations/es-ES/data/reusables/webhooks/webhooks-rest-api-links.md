---
ms.openlocfilehash: 3e175aefd9a243a098b5c35ca6d4068a651d2f61
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/05/2022
ms.locfileid: "145070130"
---
Las API REST de webhook permiten administrar webhooks de repositorio, organización y aplicación.{% ifversion fpt or ghes > 3.2 or ghae or ghec %} Puede usar esta API para enumerar las entregas de webhook para un webhook, o bien obtener y volver a realizar una entrega individual para uno de ellos, lo que se puede integrar en una aplicación o servicio externo.{% endif %}. También puede usar la API REST para cambiar la configuración del webhook. Por ejemplo, puedes modificar la URL de la carga útil, el tipo de contenido, la verificación de SSL, y el secreto. Para más información, consulte:

- [API REST de webhook de repositorio](/rest/reference/webhooks#repository-webhooks)
- [API REST de webhook de organización](/rest/reference/orgs#webhooks)
- [{% data variables.product.prodname_github_app %} API REST de webhooks](/rest/reference/apps#webhooks)

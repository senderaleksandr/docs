---
ms.openlocfilehash: 6f5f7b9a1ef172b471215d5ea66d834fb00e19d7
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/05/2022
ms.locfileid: "147423696"
---
De forma predeterminada, las instancias de {% data variables.projects.projects_v1_boards %} propiedad del usuario y de toda la organización son privadas y solo son visibles para los usuarios con permisos de lectura, escritura o administrador en la instancia de {% data variables.projects.projects_v1_board %}. {% ifversion ghae %}Una instancia de {% data variables.projects.projects_v1_board %} interna{% else %} pública{% endif %} es visible para {% ifversion ghae %}cualquiera con acceso a la empresa{% else %}cualquiera{% endif %} con la URL de la instancia de {% data variables.projects.projects_v1_board %}. Las instancias de {% data variables.projects.projects_v1_boards %} de nivel de repositorio comparten la visibilidad de su repositorio. Esto significa que un repositorio privado tendrá un proyecto privado y esta visibilidad no se podrá cambiar.

---
title: Fazer downgrade do Git Large File Storage
intro: 'Você pode fazer downgrade de armazenamento e largura de banda do {% data variables.large_files.product_name_short %} em incrementos de 50 GB por mês.'
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/downgrading-git-large-file-storage
  - /articles/downgrading-storage-and-bandwidth-for-a-personal-account
  - /articles/downgrading-storage-and-bandwidth-for-an-organization
  - /articles/downgrading-git-large-file-storage
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-git-large-file-storage/downgrading-git-large-file-storage
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - Downgrades
  - LFS
  - Organizations
  - User account
shortTitle: Downgrade Git LFS storage
ms.openlocfilehash: 9e23d3d8eaee5362375ca427a7b58505eccbaa05
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/05/2022
ms.locfileid: '145083531'
---
Quando você faz downgrade do número de pacotes de dados, as alterações entram em vigor na próxima data de cobrança. Para obter mais informações, confira "[Sobre cobrança para {% data variables.large_files.product_name_long %}](/articles/about-billing-for-git-large-file-storage)".

## Fazer downgrade de armazenamento e largura de banda de uma conta pessoal

{% data reusables.user-settings.access_settings %} {% data reusables.user-settings.billing_plans %} {% data reusables.dotcom_billing.lfs-remove-data %} {% data reusables.large_files.downgrade_data_packs %}

## Fazer downgrade de armazenamento e largura de banda de uma organização

{% data reusables.dotcom_billing.org-billing-perms %}

{% data reusables.organizations.billing-settings %} {% data reusables.dotcom_billing.lfs-remove-data %} {% data reusables.large_files.downgrade_data_packs %}

---
title:  Método SendConfigurationApplyAsync da classe MSFT_DSCLocalConfigurationManager
ms.date:  2016-05-16
keywords:  powershell,DSC
description:  
ms.topic:  article
author:  eslesar
manager:  dongill
ms.prod:  powershell
---


# Método SendConfigurationApplyAsync da classe MSFT_DSCLocalConfigurationManager

Envia o documento de configuração de maneira assíncrona para o nó gerenciado e usa o Agente de Configuração para aplicar a configuração.

Sintaxe
------

```mof
uint32 SendConfigurationApplyAsync(
  [in] uint8   ConfigurationData[],
  [in] boolean force,
  [in] string  jobId
);
```

Parâmetros
----------

*ConfigurationData* \[in\]  
Dados do ambiente para a configuração.

*force* \[in\]  
**true** para forçar a configuração a parar.

*jobId* \[in\]  
A ID do trabalho para a qual enviar a configuração.

## Retornar valor
------------

Retorna zero em caso de êxito; caso contrário, retorna um código de erro.

## Comentários

Esse é um método estático.

## Requisitos
------------
>**MOF:** DscCore.mof

>**Namespace**: Root\Microsoft\Windows\DesiredStateConfiguration


## Consulte também


[**MSFT_DSCLocalConfigurationManager**](msft-dsclocalconfigurationmanager.md)


 

 





<!--HONumber=May16_HO3-->



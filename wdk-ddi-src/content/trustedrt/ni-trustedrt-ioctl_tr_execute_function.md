---
UID: NI:trustedrt.IOCTL_TR_EXECUTE_FUNCTION
title: IOCTL_TR_EXECUTE_FUNCTION (trustedrt.h)
description: 
ms.assetid: 79daccd6-3bda-4ef2-81e4-e68137257369
ms.date: 10/19/2018
ms.topic: ioctl
req.header: trustedrt.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.max-support:
topic_type: 
- apiref
api_type: 
- HeaderDef
api_location: 
- trustedrt.h
api_name: 
- IOCTL_TR_EXECUTE_FUNCTION
product:
- Windows
targetos: Windows
ms.custom: RS5
---

# IOCTL_TR_EXECUTE_FUNCTION IOCTL

### Major Code:  [IRP_MJ_DEVICE_CONTROL](https://docs.microsoft.com/windows-hardware/drivers/kernel/irp-mj-device-control)

## -description




## -ioctlparameters

### -input-buffer



### -input-buffer-length 



### -output-buffer



### -output-buffer-length 



### -in-out-buffer



### -inout-buffer-length 



### -status-block

Irp->IoStatus.Status is set to STATUS_SUCCESS if the request is successful.
Otherwise, Status to the appropriate error condition as a NTSTATUS code. 
For more information, see [NTSTATUS Values](https://docs.microsoft.com/windows-hardware/drivers/kernel/ntstatus-values).

## -remarks

## -see-also

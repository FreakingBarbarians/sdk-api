---
UID: NF:d3d12video.ID3D12VideoEncoder.GetEncoderFlags
tech.root: mf
title: ID3D12VideoEncoder::GetEncoderFlags
ms.date: 06/21/2021
targetos: Windows
description: Gets the encoder flags with which the video encoder was initialized.
prerelease: false
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: d3d12video.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - d3d12video.h
api_name:
 - ID3D12VideoEncoder::GetEncoderFlags
f1_keywords:
 - ID3D12VideoEncoder::GetEncoderFlags
 - d3d12video/ID3D12VideoEncoder::GetEncoderFlags
dev_langs:
 - c++
---

## -description

Gets the encoder flags with which the video encoder was initialized.

## -returns

The bitwise OR combination of values from the [D3D12_VIDEO_ENCODER_FLAGS](ne-d3d12video-d3d12_video_encoder_flags.md) enumeration specified in the [D3D12_VIDEO_ENCODER_DESC](ns-d3d12video-d3d12_video_encoder_desc.md) passed into [ID3D12VideoDevice3::CreateVideoEncoder](nf-d3d12video-id3d12videodevice3-createvideoencoder.md).

## -remarks

## -see-also


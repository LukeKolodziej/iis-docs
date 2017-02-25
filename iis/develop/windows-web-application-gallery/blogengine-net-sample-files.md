---
title: "Blogengine .NET Sample files | Microsoft Docs"
author: rick-anderson
description: "This is a set of sample files you could use with Blogengine .NET and the Web Deployment tool for deploying it on IIS. The manifest.xml and parameters.xml her..."
ms.author: aspnetcontent
manager: wpickett
ms.date: 07/09/2009
ms.topic: article
ms.assetid: 
ms.technology: dotnet-webforms
ms.prod: .net-framework
msc.legacyurl: /learn/develop/windows-web-application-gallery/blogengine-net-sample-files
msc.type: authoredcontent
---
Blogengine .NET Sample files
====================
by Steve Jacobson

This is a set of sample files you could use with Blogengine .NET and the Web Deployment tool for deploying it on IIS. The `manifest.xml` and `parameters.xml` here are used to set the appropriate permissions and deploy the files to a web server . This application uses a file data store within App\_Data direcotry and hence requires that this directory have ReadAndExecute,Write,Delete permissions .

The files are annotated with comments that explain specific lines in the files you'll need to customize for your configuration.

## Sample manifest.xml file

[!code-unknown[Main](blogengine-net-sample-files/samples/sample-127306-1.unknown)]

## Sample parameters.xml

[!code-xml[Main](blogengine-net-sample-files/samples/sample2.xml)]
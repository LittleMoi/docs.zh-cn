---
title: 容器和 Docker 简介
description: 简要了解使用 Docker 所带来的主要优势。
ms.date: 04/15/2020
ms.openlocfilehash: 79b4752ef4d2f0aa6199414aea5cf4ef357c86d3
ms.sourcegitcommit: ef50c99928183a0bba75e07b9f22895cd4c480f8
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/07/2020
ms.locfileid: "87915921"
---
# <a name="introduction-to-containers-and-docker"></a>容器和 Docker 简介

*容器化是软件开发的一种方法，通过它可将应用程序或服务、其依赖项及其配置（抽象化为部署清单文件）一起打包为容器映像。然后，可将容器化应用程序作为单元进行测试，并将其作为容器映像实例部署到主机操作系统 (OS)。*

就像船只、火车或卡车运输集装箱而不论其内部的货物一样，软件容器充当软件部署的标准单元，其中可以包含不同的代码和依赖项。 按照这种方式容器化软件，开发人员和 IT 专业人员只需进行极少修改或不修改，即可将其部署到不同的环境。

容器还会在共享 OS 上将应用程序彼此隔离开。 容器化应用程序在容器主机上运行，而容器主机在 OS（Linux 或 Windows）上运行。 因此，容器的占用比虚拟机 (VM) 映像小得多。

每个容器都可运行整个 Web 应用或服务，如图 1-1 所示。 在本例中，Docker 主机是容器主机，App1、App2、Svc1 和 Svc2 是容器化的应用程序或服务。

![显示 VM 或服务器中运行的四个容器的关系图。](./media/introduction-to-containers-and-docker/multiple-containers-single-host.png)

**图 1-1**。 在一个容器主机上运行多个容器

可从容器化获得的另一个优势是可伸缩性。 通过为短期任务创建新容器，可以快速扩大。 从应用程序的角度来看，实例化映像（创建容器）类似于实例化 服务或 Web 应用等进程。 但出于可靠性考虑，在多个主机服务器上运行同一映像的多个实例时，通常要使每个容器（映像实例）在不同容错域中的不同主机服务器或 VM 中运行。

总而言之，容器在整个应用程序生命周期工作流中提供了隔离性、可移植性、灵活性、可伸缩性和可控性等诸多优点。 最重要的优点是可在开发和运营之间实现环境隔离。

>[!div class="step-by-step"]
>[上一页](index.md)
>[下一页](what-is-docker.md)

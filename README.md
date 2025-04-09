# WorkForceManager 示例应用简介

WorkForceManager 示例使用 SnapDevelop 2026 开发，展示如何通过其可视化设计器，快速实现企业员工基本管理功能。

## 应用构建步骤

以下将介绍使用 SnapDevelop 2026  构建本示例应用的关键步骤，让您直观感受其快速开发优势。

1. 启动 SnapDevelop 2026，创建类型为"浏览器端 Web 和 API“的项目，命名为 WorkForceManager.sln。

4. 选择从零开始的方式创建一系列实体。您可以打开示例中的 Database.sde 文件，了解所创建的实体，实体间的关系，和每个实体的属性。

   ![image-20250403094150736](Image/image-20250403094150736.png)

5. 在 Database.sde 设计面板中选择快速创建逻辑，基于已有的实体快速生成逻辑。除此此外，为了进行员工数据统计，新建逻辑 StatisticsService.sdlg。

   ![image-20250403095112437](Image/image-20250403095112437.png)

4. 打开每个逻辑文件，借助逻辑设计器，可以快速根据实际业务规则设计过滤器、调整、优化逻辑。例如 StatisticsService.sdlg 中的逻辑设计：

   ![image-20250403095802871](Image/image-20250403095802871.png)

5. 借助设计的逻辑快速生成前端页面，并根据需求进行调整。

   ![image-20250403095934935](Image/image-20250403095934935.png)

   如公司联系人表页面的设计：

   ![image-20250403100101381](Image/image-20250403100101381.png)

6. 点击 WorkForceManager 项目右键，选择生成项目。在生成设置中，指定将新建项目Sqlite 数据库 database.db。

   ![image-20250403100235646](Image/image-20250403100235646.png)

   SnapDevelop 将自动基于 WorkForceManager  的实体、逻辑和视图设计，生成 SourceCode 项目，其中包含标准的 Server 项目（后端项目）和 Web 项目 （前端项目）。

   ![image-20250403100536850](Image/image-20250403100536850.png)

    

## 应用运行效果

- 首页 - 数据统计

  ![image-20250403135209602](Image/image-20250403135209602.png)

- 公司管理

  ![image-20250403140241098](Image/image-20250403140241098.png)

- 员工管理

  ![image-20250403140316466](Image/image-20250403140316466.png)

## 更多信息

如需下载最新版本 SnapDevelop，欢迎访问：https://www.aipuyang.com。如需了解更多关于 SnapDevelop 的使用信息，欢迎访问：https://docs.aipuyang.com.

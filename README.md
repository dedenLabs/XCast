### 项目概述
XCast 是一个专为游戏开发、软件配置管理等领域设计的 Excel 转换工具，支持将 Excel 文件高效地转换为 JSON 或 CSV 格式。

此工具特别适用于依赖复杂数据配置和多人协作的项目（如数值策划或配置信息管理），
可生成多种编程语言和框架的解析类文件，为用户提供代码提示及 Markdown 格式注释，极大提升开发效率与数据管理标准化。

### 项目成就
> XCast 项目曾参加由 Egret 白鹭引擎主办的 **Wing IDE 开发者插件大赛**，并获得一等奖的殊荣。
此版本为基于 Adobe Air 的桌面应用，采用 AS3 语言开发，功能完备但不利于现代化扩展。
随着开源需求增加，近期已启动源码转换工作，目标是使其支持更广泛的开发环境和用户需求，开源发布也指日可待 

### 核心功能

- **多国语言支持**：便于全球化项目应用，支持多语言配置。
- **严格类型与复杂字段**：提供字段严格类型检查，支持复杂字段关系（如“引用”、“接口”、“嵌套”）的灵活配置，确保数据一致性和完整性。
- **多平台解析类生成**：可生成多种目标环境的解析类（如 TypeScript、Unity、Unreal Engine、Node.js、Go、Python、C++ 等），为开发者提供即用的高效代码。
- **代码提示和注释支持**：生成的解析类文件支持代码提示，并自动从 Excel 中获取注释（Markdown 格式），便于开发人员快速掌握配置内容。

### 适用场景
XCast 特别适用于对配置文件和数值设定要求较高配置管理需求的项目：

- **游戏开发**：适合数值策划、逻辑配置及多人实时协作的开发项目，解决版本管理和数据一致性难题。
- **企业软件配置**：适合管理、标准化软件项目的配置数据，实现高效同步、转换和使用。

### 技术栈
XCast 将使用现代化技术栈进行重构，以增强扩展性和适应性，使其可在多种开发环境和系统上高效运行。

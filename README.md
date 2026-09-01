这是一款用于二次封装Windows 系统的工具，一般用于企业内部或者其他装机人员，将纯净版Windows安装、配置成符合后续装机的状态后，可使用此工具配合PE系统，二次封装，生成WIM压缩文件，支持WDS（PXE安装系统）服务器。

主体步骤分为2个阶段：
第一阶段是在Windows 10环境下，待安装好需要封装的软件、文件后，开始封装。

第二阶段在PE环境，导出WIM（封装好的镜像），支持导入的WDS服务器实现PXE安装系统，无人值守，安装完成后直达桌面。

<img width="1021" height="1368" alt="111" src="https://github.com/user-attachments/assets/f98985b8-ae1b-49f2-bb80-1defec4f488d" />
<img width="1021" height="762" alt="222" src="https://github.com/user-attachments/assets/acc75b4d-2929-4b3d-aec2-5bc2898b169e" />

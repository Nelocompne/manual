public:: true

- 更新时间:: [[Mar 7th, 2024]]
  tags:: PDF
- ## 准备：
	- [clawsoftware/clawPDF: Open Source Virtual (Network) Printer for Windows that allows you to create PDFs, OCR text, and print images, with advanced features usually available only in enterprise solutions. (github.com)](https://github.com/clawsoftware/clawPDF)
- ## 安装clawPDF
	- ![安装clawPDF.mp4](../assets/安装clawPDF_1709822469353_0.mp4)
- ## clawPDF虚拟打印机配置设置
	- ![clawPDF虚拟打印机配置设置.mp4](../assets/clawPDF虚拟打印机配置设置_1709822484400_0.mp4)
	- 打开“clawPDF”虚拟打印机选项设置，“高级”，“文档选项”-“PostScript选项”-“镜像输出：是”。
- ## clawPDF配置及打印
	- ![clawPDF配置及打印.mp4](../assets/clawPDF配置及打印_1709822491978_0.mp4)
	- 开始菜单找到“clawPDF”，“文件参数设置”：
		- 保存：转换后使用标准查看器打开，关闭，在批处理任务下避免重复打开。
		- 自动保存：启用自动保存，开启，在批处理任务下避免手动保存。
		- 动作：打印文件，开启，将输出的处理自动跳转到打印流程。
	- 打印时，选择“clawPDF”虚拟打印机进行打印，之后再从打印机选项中选择实际打印机打印。
- 优点：Windows多版本集成，开源，集成GhostScript。
- 缺点：打印处理本质为将输出的PDF文件进行打印，如文档内容复杂度高，面对性能较慢的机器需要花费更多时间。
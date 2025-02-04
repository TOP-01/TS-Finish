# TS Finish

TS Finish is a powerful MPEG-TS packet processing tool. It modifies the MPEG-2 transport stream without changing the original packet payload. It adds, modifies and extracts MPEG-TS packets according to user needs. TS Finish gives user the convenience of editing the underlying data of MPEG-TS.

TS Finish是一款功能强大的MPEG-TS数据包处理工具。它能够在不更改原始数据包有效负载的情况下修改MPEG-2传输流。它能够根据用户需要添加，修改和提取MPEG-TS数据包。TS Finish为用户提供了编辑MPEG-TS底层数据的便利。


![TS Finish preview](https://thumbs2.imgbox.com/59/19/E2adcaNt_t.png)


# Software features / 软件功能

- Rebuild PAT, PMT and SDT tables.

- Change specific PID values.

- Discard, insert, cut out data packets.

- Concatenate file processing.

- DSM-CC Download Data Block (DDB) data extraction.

- English language support.

---

- 重建PAT，PMT和SDT表格。

- 变更特定轨道的PID值。

- 随机丢弃、插入、截取数据包。

- 多文件合并处理。

- DDB数据提取。

- 简体中文语言支持。


# System requirements / 系统要求 

Applicable for Windows 7 and above operating systems.

适用于Windows 7及以上操作系统。


# Changelog / 更新日志

**10.6.3 (2022/02/01)**

1.修复了合并文件功能无法正常工作的问题。

2.调整了TS包的默认插入周期。

3.修正了一个英文词条。

---

**10.6.2 (2021/08/17)**

1.增加了适用于PMT表格重建功能的音频编码定义模块。该模块可解决AC-3音频流的流类型被标记为0x06后，无法被主流媒体播放器识别的问题。

2.修复了在软件中填写大于Int32最大值(2147483647)的ID时，无法被正确处理的问题。

---

**10.6.0 (2021/01/02)**

1.进一步优化主处理模块代码，可提升5-10倍以上的处理速度。

2.修复了重写包计数器功能中的一个严重逻辑错误。

3.修复了提取DDB数据时，可能导致数据无法提取成功的一个标记判定错误。

4.永久移除了已过时的过滤器功能。

---

**10.5.1 (2020/06/28)**

1.修复了填写16进制ID时，因数据转换错误，从而导致输出的TS流中ID出现误差的问题。

---

**10.5.0 (2020/06/01)**

1.新增支持修改指定轨道的PID。推荐您配合PAT/PMT表格重建功能使用。

2.新增支持RTP流的录制文件输入。此功能可能在未来完全替代现有的"过滤"功能。

3.新增支持M2TS格式的视频流的文件输入。

4.新增支持TS包头分析功能。可以快速转换TS包头的十六进制值为完整文字信息。

5.新增支持重写TS包头加扰标记。如果您将此值设置为非0x00的值，则您需要添加应用标记的PID的流类型。

6.新增支持单击"输入文件"或"输出文件"标签一键打开对应目录。

7.开始任务后，若您未选中任何PID，则"使能PID过滤器"选项将自动去使能。优化此项后，将避免因人为疏忽导致输出空文件的现象。

8.调整功能标签顺序为更常用的顺序。

9.修改了一些默认设置为更合理的值。

10.增加国标AVS3编码标记至默认流类型列表，并优化其他默认流类型列表项目的排序。

11.优化使用"截取"功能实现多任务队列时的文件命名逻辑。

12.优化少量程序逻辑，避免了一些运行时的程序问题。

---

**10.3.2 (2020/05/21)**

1.修复在更新至10.3.1版本的软件后，使用截取功能有概率无法应用正确的结束点的问题。

---

**10.3.1 (2020/05/20)**

1.修复使用截取功能并添加多个任务时，可能会导致的输出文件持续膨胀无法自动结束的问题。

2.修复使用截取功能并添加多个任务时，触发停止操作不生效的问题。

3.优化部分代码，提升工作效率。

---

**10.3.0 (2020/02/08)**

1.优化处理代码，大幅提高处理效率。

2.增加任务完成提示音。

3.增加了一些简体中文词条翻译。

4.细节修改。

---

**10.2.3 (2019/12/09)**

1.修复了执行队列任务时，除首个任务外无法正确显示进度的问题。

2.增加了在一些场景下的提示对话框。若有任务正在执行时，关闭窗口会显示确认提示。

---

**10.2.2 (2019/11/21)**

1.优化重建PMT表格时选择PID的算法。

2.标题栏状态细节变化。

---

**10.2.1 (2019/11/12)**

1.修复使用截取功能时使用时间表达式无效的问题。

---

**10.2.0 (2019/10/27)**

1.增加剩余工作时间估算指示。

2.修复在某些特定情况下，任务完成后再次扫描新的输入文件，会导致扫描出错误PID的问题。

---

**10.1.0 (2019/09/30)**

1.增加Download Data Block (DSM-CC)文件块提取功能，可指定ID提取同轴中的DVB广播文件，例如机顶盒固件升级包。

---

**10.0.1 (2019/09/27)**

1.修复"仅提取有效荷载"功能使能后不生效的问题。

2.修正了一个翻译词条。

# ICSE-2012-Spy-Runtime

This repository contains information related to the tool Spy@Runtime presented at the International Conference on Software Engineering, 2012. The tool was originally presented in [this paper.](http://dl.acm.org/citation.cfm?id=2337430)


This repository <b><i>IS NOT</i></b> the original repository for this tool. Here are some links to the original project:

[The Official Project Page, including source code](http://www.inf.usi.ch/postdoc/mocci/spy-testing/index.xhtml)
[The Tool on the Visual Studio Gallery](http://www.inf.usi.ch/postdoc/mocci/spy-testing/tool.xhtml)
[A Video of the Tool](https://youtu.be/EqQ7k_UG448)

In this repository for Spy@Runtime, you will find:

:white_check_mark: Source code (available)<br>
:white_check_mark: The original tool (available)<br>

Instructions to Run - <br>
-Follow the steps given in the Tool website. <br>
-Use <b>./run-spy-quick.sh -w it.polimi.dei.spy.wrappers.StorageServiceClientViewWrapper storageServerClient.StorageServiceClientView</b> for Model generation and 
<b>./run-monitoring.sh config/monitoring-storageservice.xml  storageServerClient.StorageServiceClientGUIToMonitor</b> command to enable Monitoring facility instead of using the corresponding commands given in the website. <br>

This repository was constructed by [Sindhu Vairavel](https://github.com/SindhuVairavel) under the supervision of [Emerson Murphy-Hill](https://github.com/CaptainEmerson). Thanks to Mario Sangiorgio and Andrea Mocci for their help in establishing this repository.

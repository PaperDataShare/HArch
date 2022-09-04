Supplemental materials of our ICSE 2023 paper: Identifying History-based Architecture Hotspots

Source code: All the source code can be downloaded from GitHub:
Accumulo: https://github.com/apache/accumulo/   Release 1.9.3
Ambari: https://github.com/apache/ambari		Release 2.7.3
ActiveMQ: https://github.com/apache/activemq	Release 5.15.9
Cassandra: https://github.com/apache/cassandra	Release 3.11.4
CXF: https://github.com/apache/cxf				Release 3.3.2
Hadoop: https://github.com/apache/hadoop		Release 3.1.2
HBase: https://github.com/apache/hbase			Release 2.2.0
Hive: https://github.com/apache/hive			Release 2.3.5
PDFBox: https://github.com/apache/pdfbox		Release 2.0.16
Wicket: https://github.com/apache/wicket		Release 8.5.0


data/

*_git.log: a project's revision history.

*_filelist.csv: a project's file list extracted from its source code.

*_BC_##.csv: each file lists the bug churn of each file by examining the revision history coverd by an evolution window. 

*-hdp_##.dsm: the H-DSM derived form the revision history coverd by an evolution window. 


bug-issue/

*-jira-bugs.zip: a project's bug records extracted from its issue tracking system, JIRA.


rq_result/

.xlsx: the results of each research question.

tool/

HDSMGenerator.jar: the tool for generating a h-dsm.

ArchHotsoptDetector.jar: the tool for detecting history-based architecture hotspots.

BugChurnCalculator.jar: the tool for calculating the bug churn of each file.


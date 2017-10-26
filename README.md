# ManicTime data set

## SUMMARY ##

ManicTime data set was collected by Lichao Liu in the year 2014 when he was a master student 
at School of Software, Tsinghua University. 

Dr. [Jun Chen](https://chenjun082.github.io) was granted by Lichao Liu to use the data in his research and publish the data set.

This data set consists of 577,577 records of the usage logs of 1164 applications on personal computers from 44 graduate students at Tsinghua University.

The records were collected using a software called [ManicTime](http://www.manictime.com/) which tracks the time of focus-in, focus-out and duration of the application usage on PC （for example, switch from Microsoft Office Word to Chrome). The participants were aware that the data were collected only for research purpose and their names would be anonymized when published.


## STATS ##
<table>
    <tr>
        <td>44</td>
        <td>users</td>
    </tr>
    <tr>
        <td>1164</td>
        <td>applications (identified by the application name)</td>
    </tr>
    <tr>
        <td>577,577</td>
        <td>records in all</td>
    </tr>
</table>


## FILE FORMAT ##

Each file contains a user's usage logs.
In a file, each line has the following format:

*Focus-in timestamp \t Focus-out timestamp \t Duration \t Application name*

Please note that the switching of tabs in web browsers will also be recognized as a focus-out of the previous tab and a focus-in of the current tab.
 

REFERENCE 
=============================================

When using this dataset you should cite:

<pre>
<code>
@INPROCEEDINGS{JunChen:aaai2015,
  AUTHOR = {Jun Chen and Chaokun Wang and Jianmin Wang},
  TITLE = {Will You ``Reconsume'' the Near Past? Fast Prediction on Short-Term Reconsumption Behaviors},
  BOOKTITLE = {Proceedings of the Twenty-Ninth AAAI Conference on Artificial Intelligence},
  PAGES = {23-29},
  YEAR = "2015",
} 
</code>
</pre>

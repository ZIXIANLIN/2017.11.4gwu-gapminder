#Crawle Cragislist

## Introduction
* crawler function: synchronized crawler 
* crawler method: observe the difference of selector path, and iterate 1-20 paths to get the information 

## jar
jsoup-1.10.1.jar

## Run the code
open the project in the intellij --> click run

## Results
![results](https://github.com/zhewangjoe/CS502-1801/blob/zixianlin/ZixianLin/P2_exam/rentCrawler%20results.PNG)

#Spark job

##avg bid price

python avgBidPrice.py /home/zoe/Desktop/CS502-1801/CS502-1801/ZixianLin/P2_exam/spark/data/ads_0502.txt avgBidPrice


##budget/bidPrice ratio

python click_times.py /home/zoe/Desktop/CS502-1801/CS502-1801/ZixianLin/P2_exam/spark_job/data/ads_0502.txt /home/zoe/Desktop/CS502-1801/CS502-1801/ZixianLin/P2_exam/spark_job/data/budget.txt clickTimes


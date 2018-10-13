This is a scrapper that goes through www.ralphlauren.co.uk
and stores all the tag,price and image links in a csv 
file using the library scrapy.

To create a spider ,type the command 
	scrapy genspider botname www.examplelink.com

To run the spider , execute the command:
	scrapy crawl ralphbot

The results will be stored in a csv file and will be stored 
in the directory where the above command was executed .
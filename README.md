# Hello world!

Hi there. This is my first attempt to make a data analysis process! The whole process is quite simple: spidering data , analysizing data ,and finally get conclusion. Tools used in this project is Python and Excel. In order to master python as soon as possible, so we will use python more in this project. Well, because this is my first project and at the same time I am the newer of python, there will be a lot of bugs and flaws in the process . So, this project is just a attemptation involved less reference meaning. But truth is , which I believe , my second project will be better that could provide a good insight for readers. I hope that day comes soon!

STEPS:
1. Find data structure of 51job.com, then dig it via  python spider.
2. Clean up the data.
3. Use python to find the hide information from disposed data.
4. Express info via chart and graph.
5. Write it to Github.
6. Make a cup of coffee.

HERE WE START !

# Step1: Coding a spider.
Before coiding a python spider, we should visit the web page first.In this project, our target web page is [51job.com](https://search.51job.com/list/020000,000000,0000,00,9,99,%2520,2,1.html?lang=c&stype=&postchannel=0000&workyear=99&cotype=99&degreefrom=99&jobterm=99&companysize=99&providesalary=99&lonlat=0%2C0&radius=-1&ord_field=0&confirmdate=9&fromType=&dibiaoid=0&address=&line=&specialarea=00&from=&welfare=) . We can filter the results via adjust the key bottoms. Such as change the __location__ into __Shanghai__.And after that, the web url will __changed__!.So, for getting the correct data, we can filter the jobs data via web-builded-in funcions.After set a lot of constrains. We can get the **url** , and this **url** is our final target!

Click into the web page. 

# ICP3

In Class Programming for the utilization of classes, inheritance, web-scraping, and Numpy.

Marcus Wong Ken Ji

2/5/2021

Description of ICP: Creating classes, learning about how inheritance works, importing scientific python packages and using them, Web scraping and extracting data through wikipedia pages.

#Question 1 Code

![image](https://user-images.githubusercontent.com/72952948/107092328-0383f880-67c9-11eb-82c4-8b553ecf4ee5.png)


![image](https://user-images.githubusercontent.com/72952948/107092395-24e4e480-67c9-11eb-8820-d31de78d00ea.png)

I started by creating a class 'Employee' and a class 'Fulltime Employee' that inherited the properties of 'Employee'. I also created adata member that counted the number of 'Employee'. I then used constructors that initialized the name, family, salary, and department for the Employee class. I also created a function that calculated the average salary of all Employees. Lastly, I printed all the relevant information for each Employee along with the average salary of the employees.

![image](https://user-images.githubusercontent.com/72952948/107093188-75a90d00-67ca-11eb-9c3d-db3cc76eac4d.png)

#Question 2 Code

![image](https://user-images.githubusercontent.com/72952948/107093396-c6206a80-67ca-11eb-8fdb-720adf012c43.png)

I started by importing the libraries and used the request.get url to obtain data from the specific wiki page.Then, I opened a text file named 'wikilinks.txt' to append the information and print the title of the page. I also used elem.xpath to navigate through the elements and obtain the 'href' elements as strings. I then print all the links to the output text file named 'wikilinks.txt'

![image](https://user-images.githubusercontent.com/72952948/107108360-e406c300-67fc-11eb-95a6-83183b1ca0fe.png)




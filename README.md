# student-data-manager
 A simple console program to manage student's official data using c++ .Store records like student_id, name, course, department, phone no. etc. It writes records into a .csv file that can be opened with any spreadsheet software like google sheets,microsoft excel.
Note As I have used the linux/unix specific library unistd.h to use functions like sleep() and system("clear"), the cpp files will only compile on linux/unix based operating systems. Soon I'll be adding detailed steps on changes to be made to compile these files on other operating system like Windows.

Why .csv file?
As we all know, CSV(Comma Separated Values) files are easier to share as it can be opened with any spreadsheet software like Google Sheets, Microsoft Excel, Libreoffice calc etc. that makes it highly portable as you can share the datas for operation to anyone if needed. It doesn't need the same Student Manager Program to view the datas in easy table format, anyone can view it with other softwares mentioned.

Features available-
Add Student Records
Duplicate id won't be added.

View All Records
Total Records Table View.

Update Records
You can update student records and there's an option to cancel all changes while updating.

Delete Records
Delete Any Student's Records by Id.

Search
View any Student's Records by Id.
<h1>screenshots of the program running in terminal</h1>
![admin_menu](https://github.com/iamashishxo/student-data-manager/assets/79656682/605f0c65-4f7b-4ae1-ac92-e8b6a87fefd2)
![view_record](https://github.com/iamashishxo/student-data-manager/assets/79656682/0ecbde82-6692-4ad0-ab6c-112c368833cd)
![delete_record](https://github.com/iamashishxo/student-data-manager/assets/79656682/6ae17e4c-0c6c-4f44-a272-966a2a26d68e)




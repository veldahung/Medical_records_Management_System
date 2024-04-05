About this course
===
Database Management 資料庫管理

Second Semester, 2023

Introduce the fundamental concepts necessary for designing, using, and 
implementing database systems. The course stresses the fundamentals of database modeling and 
design, the languages and facilities provided by database management systems, and system 
implementation techniques. 

Progress
===
1. DB system architecture
2. Relation model
3. Introduction to SQL
4. ER model, EER, mapping
5. File storage, indexing
6. Normalization 

Homework
===
HW1: PHP(self-study)

HW2: CV web page

HW3: Login system based on HW2

Final Project: Health Information Management System


Grades
===
Midterm (35%), Homework & Project (25%), Final (35%), Participation (5%)

Final score: A+


Health Information Management System
===
DB Final Project: 身體健康資料管理系統 Health Information Management System

### Motivation
爲因應與陽明校區合作及外部醫院的產學合作，我們希望建立健康檢測資料庫來協助醫師更有效率的瞭解病人狀態

### Usage
1.病人查詢自己歷次看診記錄

這個功能允許病人查詢他們過去所有的看診記錄。病人可以通過這個功能來追蹤自己的健康狀況，瞭解他們過去曾經生什麽病，花了多少看診費，看了什麽醫生等情況，並與過去的結果進行比較，這樣的資訊可以幫助病人和醫生更容易掌握病人的狀況。

2.病人查詢特定專科的醫生

這個功能可以讓病人查詢特定專科領域的所有醫生或特定的醫生。病人通過選取專科的名稱，顯示相關的醫生列表。病人將看到醫生的性別、ID、email、電話、平均評分。這樣的功能可以讓病人找到適合的專科醫生，尋求專業的醫療治療。

3.病人對醫生進行評價

此項功能有助於未來提供更好的醫療服務和改善醫生與病人關係。病人通過給予醫生評分，表示對此次看診的醫生提供的服務的滿意程度。對於醫生來説，爲了不要讓自己的平均評分太過於低而可能遭受懲罰，醫生會進行更好的反省及改善自己，提高服務質量。這些評分是匿名的，以保護病人的隱私。此評分也方便病人進行醫生的選擇。

4.醫生查詢全部健康檢測記錄

這個功能允許醫生查詢病人的所有健康檢測記錄，讓醫生利用此功能查看病人過去的健康趨勢和治療進展，有利於醫生幫他們制定個性化的治療計劃和更瞭解病人的身體狀況。

### Website View
醫生/病人登入介面：

用戶在登入介面時選擇自己的身份，輸入當初在註冊時候的名稱和密碼。若名稱和密碼都正確，就能成功登入。
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/1.jpg)
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/6.jpg)


醫生/病人註冊介面：

第一次使用此系統的用戶需要先進行註冊，醫生和病人的註冊要求的資料皆有：姓名、性別、生日、身份證字號、email、電話號碼、密碼。不同的是，醫生需要選取自己所屬的部門，而病人需要選取自己的血型，並輸入身高和體重。
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/2.jpg)
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/7.jpg)


醫生/病人個人簡歷：

在醫生和病人個人簡歷部分，該介面顯示了所有用戶在註冊時所提供的資料。但是，醫生的個人簡歷中的部分多了所有看過的病人給的評價的平均分數。病人的個人簡歷中，還會有身高、體重和血型的部分。而簡歷的大頭貼是依照性別產出的。
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/3.jpg)
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/8.jpg)


醫生新增看診記錄：

醫生每次病人時，可以新增看診記錄，新增紀錄時需填入病人編號、看診日期、病人的疾病、看診費用和開給病人的藥物。
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/4.jpg)


醫生查詢看診記錄：

以下圖片為所有醫生的看診記錄，醫生可以查看其自己所有的看診紀錄。
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/5.jpg)


病人查詢特定專科的所有醫生：

病人可以選擇一個部門後並在選擇醫生的地方選擇-，就會出現該部門所有的醫生，同時附上醫生的相關資訊，例如：性別、ID、email、電話、平均評分等，供病人選擇適合自己的醫生。
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/10.jpg)


病人查詢特定專科的醫生：

病人可以選擇一個部門後再選擇醫生，就可以用此系統查詢特定的醫生。
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/11.jpg)


病人查詢自己的看診紀錄並評分：

病人可以查看自己的所有看診記錄，包括了症狀、挂號費、藥物等。病人也可為每次的看診給予該看診醫生評分，評分預設為NULL，在更新評分處選取評分後會顯示在目前評分。
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/12.jpg)


病人查詢自己的看診紀錄並評分（更新後）：

以下為病人評分以後的介面，病人是可以更改評分的。
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/13.jpg)


病人查詢自己歷次健康檢測記錄：
![image](https://github.com/barrenshore/202302-Database/blob/main/Final_Project/final_project_group1/website%20view/14.jpg)

# AutopsyForensics

Autopsy

In this lab I learned how to use Autopsy software for forensics to narrow down clues and important information within data provided. I learned to be patient in looking for information that could help me solve the case in hand. Going to solve some cases and make a report after.

Case 1
In this case a suspicious death occurred where Joshua Zarkan found his girlfriend dead in her apartment and reported it to officials. Officers seized a USB drive and a crime scene evidence technician skilled in data acquisition made an image of the drive with FTK imager and secured the drive and placed it in a secure evidence locker at the police station. I received the image file from the detective and directs me to examine it and identify any evidence artifices that might relate to the case. 
Started up autopsy and loaded the image into the software.

 <img width="615" height="249" alt="image" src="https://github.com/user-attachments/assets/950ebaa6-af23-42cc-837b-4bd217c0ffcd" />
 
<img width="605" height="245" alt="image" src="https://github.com/user-attachments/assets/90748af4-7504-4e32-8091-beb6e29dd7a7" />

The data source is the image or a VM file.
 
<img width="504" height="231" alt="image" src="https://github.com/user-attachments/assets/58d8a934-7817-4958-9f5b-958ee9cb7b16" />

In the ingest module I selected all
 
<img width="706" height="390" alt="image" src="https://github.com/user-attachments/assets/2c4f4aab-8c33-4b98-a734-54c4708d45f7" />

In the Tree Viewer pane on the left I could see different sections and expand views, file types, by extension, and document. I could view each each subfolder under document and determine which folder might contrain files of interest to this case.
 
<img width="790" height="433" alt="image" src="https://github.com/user-attachments/assets/3b6cef3b-c3cb-43a9-b3c2-cc0dc4e99f04" />

In the office sybsection I noticed a vls file which is an excel sheet with some information on it made by Amelia Phillips.
 
<img width="636" height="544" alt="image" src="https://github.com/user-attachments/assets/4be1d8cd-6efb-4e79-ba0e-c9de0b01816d" />

Upon further investigation I noticed a txt file in the plain text subsection and downloaded it to reveal its content.
 
 <img width="803" height="407" alt="image" src="https://github.com/user-attachments/assets/33917242-63d0-4a5a-a85c-ba913cc5e38c" />

 <img width="568" height="418" alt="image" src="https://github.com/user-attachments/assets/34e24945-445f-40f6-b030-7a941988a2a8" />

<img width="569" height="181" alt="image" src="https://github.com/user-attachments/assets/8f04738d-ae7a-4d92-a25d-3ab2ad152a04" />

Report
This case is a suicide. The victim was called Sylvia and she was found by her boyfriend named Joshua Zarkan. On her usb it contained 2 files of significance. One file was a text file which contained a suicide letter claiming she cannot go any longer that she needed help which was created on the 9th of December 2005 at 9:48 EST and was modified on the 22nd of November 2002 at 20:29:46 EST. Another file contained all of Sylvia’s assets which included stocks, bonds, real estate, annuities, savings, and life insurance all of which totaled to $2,796,000.00. the file of her assets was made by on excel by Amelia Philips who works for the company starships CMS which was created also on the 9th of December 2005 at 00:00 but was modified on the 23rd of November 2002 at 4:26:26 EST.
	The excel file with her assets was made before the suicide text note pleading for help. Only thing fishy was that the modification dates are 2 years before the date they were created. Although she had a boyfriend and a lot of money, she could have killer herself solely because she was not happy with life and was going through things internally.
 
Case 2
In this case I work for a corporation’s IT Security Department. My duties include conduction internal digital investigations and forensics examinations on company computing systems. A paralegal from the law department Ms. Jones asks me to examine a USB drive belonging to an employee who left the company and now works for a competitor due to the concerns that the former employee might have been an insider threat and possessed sensitive company data. I was also told that the former employee had access to confidential documents because he was someone saw him accessing his manger computer on his last day. My task is to find out if it contained any such documents.
Loaded the image on autopsy.
 
 <img width="558" height="300" alt="image" src="https://github.com/user-attachments/assets/540d3a2c-9ef6-48e0-b0f3-044bcccfcd1d" />

<img width="786" height="257" alt="image" src="https://github.com/user-attachments/assets/b44c012a-cb54-4ad7-8b35-975d5b7d973d" />

I clicked on the keyword search and typed in the word “confidential” which brought up files that has that label.
 
 <img width="866" height="291" alt="image" src="https://github.com/user-attachments/assets/2d11704c-c86c-42e8-b6e3-849f49e18aa7" />

<img width="792" height="273" alt="image" src="https://github.com/user-attachments/assets/d1f94a80-a512-4cea-a61b-0bf67c4ea34c" />

I recovered those files, so I could do further inspection and named it to find it easily. 
 
 <img width="564" height="355" alt="image" src="https://github.com/user-attachments/assets/418e09f3-a483-4c38-953a-3d3ef2abe8e5" />

 <img width="593" height="344" alt="image" src="https://github.com/user-attachments/assets/c5697da9-e881-4df6-9ffc-470d0801eb46" />

<img width="707" height="205" alt="image" src="https://github.com/user-attachments/assets/82e1ce09-3bcb-47a9-bcc5-b5c5a1458672" />

The generated report window I clicked results-excel option button in the report modules section. In the configure artifacts report window I clicked tagged results and reovered office documents. Then clicked results – excel pathname to open the excel report.
 
 <img width="386" height="305" alt="image" src="https://github.com/user-attachments/assets/8852006d-b0a0-427b-be71-255327e6c5be" />

 <img width="784" height="236" alt="image" src="https://github.com/user-attachments/assets/44e8a4fa-ec97-4250-b0e8-58ff917c70f8" />

<img width="661" height="509" alt="image" src="https://github.com/user-attachments/assets/79013c10-2da9-413a-ad4a-dab13cff91c7" />

Report
Here is me listing the filenames where I found a hit for the keyword. There were no hits in unallocated space.
a.	First test results
b.	Message_o091x
c.	Message_l841x
d.	Message_a193x
e.	Message_l890x
f.	Message_h972x
g.	Message_s528x
h.	Message_l432x
i.	Message_j465x

Case 3
In my last case I am an IT security specialist for Superior Sailmakers, a company making sails for sloops and yawls. It sells rigging and sails to many sailboat makers who are competing against one another. Ms. Olsen in the human resources department notifies me that she got an anonymous letter with an old USB drive.  The letter states that a former employee ralph Williams had photos belonging to AC sailboats that contained trade secrets from April 2006 and that after Mr. Williams ended his employment in January 2007, he used photos on the USB drive to get hired by smith sloop boats competitor. I have to examine the contents of any photos to determine whether the anonymous complain it true. 
 
 <img width="287" height="325" alt="image" src="https://github.com/user-attachments/assets/8f033781-e625-41e3-aa70-9515f51c2b1b" />

 <img width="480" height="251" alt="image" src="https://github.com/user-attachments/assets/d5fa822a-fdc3-4e10-b3dc-99f93b771be2" />

<img width="671" height="188" alt="image" src="https://github.com/user-attachments/assets/64d4a33c-d9a5-45f0-a464-26ee632e0946" />

In the images subsection in the pane I could see multiple images and sorted the column by clicking modified time header.
 
<img width="489" height="510" alt="image" src="https://github.com/user-attachments/assets/fedee2f5-034a-46e0-8931-9251f032ec16" />

Found the first image starting with april 2006 and clicked the file to view its content.
 
<img width="653" height="314" alt="image" src="https://github.com/user-attachments/assets/c8bba540-2a49-4450-96f4-a438f9058aa2" />

<img width="650" height="341" alt="image" src="https://github.com/user-attachments/assets/2d891027-7a71-49ed-9909-b23466ad2c39" />

After viewing all the images I selected the ones that had boats in them using ctrl+click then tagged the file with quick tag feature then follow up
 
<img width="685" height="390" alt="image" src="https://github.com/user-attachments/assets/f23ede8d-2383-468c-a669-c1d8270ac174" />

<img width="575" height="438" alt="image" src="https://github.com/user-attachments/assets/1c3c9977-3911-41c3-b180-d022faaf86c4" />

<img width="605" height="632" alt="image" src="https://github.com/user-attachments/assets/bd7a8576-4a74-4278-9d9b-7bdbed896e78" />

<img width="608" height="635" alt="image" src="https://github.com/user-attachments/assets/1c394180-02ce-4913-abe2-76e6f141dac2" />

<img width="550" height="574" alt="image" src="https://github.com/user-attachments/assets/60987411-b572-4659-9a10-5c25ed92d78f" />

Using those images I generated a report then clicked results- HTML option.
 
<img width="614" height="148" alt="image" src="https://github.com/user-attachments/assets/99aecf38-b9e5-4f70-b132-095d5c4626f3" />

In the report generated progress window I clicked results – HTML pathname to view it then could click the links to examine the tagged files.
 
<img width="358" height="397" alt="image" src="https://github.com/user-attachments/assets/f9eb668f-1933-4d90-888f-1da21bbc4284" />

 <img width="346" height="419" alt="image" src="https://github.com/user-attachments/assets/13ef15ff-ae68-41e7-b652-7befa4fca9e3" />

Report
From my findings there were 477 images. There were only 3 pictures that contained a boat or part of a boat. One was attached to the back of a car. One was the front part of a boat where someone could hold on to while sailing and the other was the frame of a boat that was not fully made yet.

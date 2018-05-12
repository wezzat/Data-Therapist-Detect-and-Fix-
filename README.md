# Data-Therapist-Detect-and-Fix-
Is a set of open source tools and programs that can run on any platform to detect the corruption in data online and fix most of it transparently while the system is up and running without compromising the system availability. DT (Data Therapist) has been used in different industries and proven its success across platform and with different datatypes such as: char, nchar, nvarchar2, varchar, long, raw, long raw, number, numeric, float, decimal, integer, double precision, etc. The main objective of Data Therapist platform is to provide Database Administrators, Data analysis and IT Managers best practice recommendations for configuring key parameters, database features, system features and operational practices to enable best corruption detection, prevention, and automatic repair, in a MAA (Maximum Availability Architecture) or Data Guard configuration. This platform also provides additional background information on each parameter and performance consideration. Data Therapist (Detect and Fix) platform can deal with all types data corruption across different database systems running on different Operating System by detecting the suspicious data blocks, determine if they are really corrupted, specify whether the corruption is logical or physical and fix the corruption online while the system is up and running. The theory behind Data Therapist is simple, however it is so powerful, it is based on data detection algorithm that expect the data within a data block by knowing the data in the previous and next block to the suspicious block, from the data chain/sequence as well as its checksum it can detect and expect the corrupted data and fix it online. 
A corrupt block is a block that has been changed so that it differs from what the Database expects to find. The Data Therapist platform deals with two data block corruption types:
•	Physical block corruption:
 Which is also called a media corruption, the database does not recognize the block at all: the checksum is invalid or the block contains all zeros.  An example of a more sophisticated physical block corruption is when the block header and footer do not match.
•	Logical block corruption:
The contents of the block are physically sound and pass the physical block checks; however the block can be logically inconsistent. Examples of logical corruption include incorrect block type, incorrect data or redo block sequence number, corruption of a row piece or index entry or data dictionary corruptions.    
Block corruptions caused by stray writes, lost writes or misdirected writes can also cause havoc to the database system availability. The data block may be physically or logically correct but in this case the block’s content is older or stale or in the wrong location. 
Block corruptions can also be divided into interblock corruption and intrablock corruption:
•	Intrablock corruption, the corruption occurs in the block itself and can be either a physical or a logical corruption.
•	Interblock corruption, the corruption occurs between blocks and can only be a logical corruption.
Data Therapist (Detect and Fix) platform can deal with all types data corruption across different database systems running on different Operating System by detecting the suspicious data blocks, determine if they are really corrupted, specify whether the corruption is logical or physical and fix the corruption online while the system is up and running.
The theory behind Data Therapist is simple, however it is so powerful, it is based on data detection algorithm that expect the data within a data block by knowing the data in the previous and next block to the suspicious block, from the data chain/sequence as well as its checksum it can detect and expect the corrupted data and fix it online. 

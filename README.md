# SCUT-SFVD
SCUT-SFVD: A Finger Vein Spoofing/Presentation Attack Database

## Short Information
SCUT FV Presentation Attack Database (hereinafter: SCUT FVD) is used for scientific research of finger vein recognition. It is collected by BIP Lab, School of Automation Science and Engineering, South China University of Technology(SCUT). Any one or group is allowed to use this database free of charge.  


The data is split into 3 sub-groups comprising:
1. Training data ("train"), to be used for training your anti-spoof classifier;
2. Development data ("dev"), to be used for threshold estimation;
3. Test data ("test"), with which to report error figures;
Clients that appear in one of the data sets (train, dev or test) do not appear in any other set.


## File Naming Convention
Images are labeled as follow: ID_finger_session_shot_light.bmp,  
where “ID” stands for client's ID, 
“finger” ranges from 1 to 6 standing for the index, middle and ring finger of right and left hand respectively,
“session” stands for session number which can be "0" or "1"   
“shot” stands for the considered shot number ranging from 0 to 5,
and “light” stands for the level of light intensity which can be an integer between 1 and 6.  

Images from the same client are regrouped into a single folder labeled.

NOTE: When processing these images, you only need to consider the first two label, i.e. “ID” and “finger”. 

* Example of the nomenclature for the real images from the client #1:    
  *real/1/1_1_1_0_5.bmp    
  *real/1/1_1_1_1_5.bmp    
  *real/1/1_1_1_2_5.bmp   
  *real/1/1_1_1_3_5.bmp    
  *real/1/1_1_1_4_6.bmp   
  *real/1/1_1_1_5_5.bmp   
* Example of the nomenclature for the spoofing images from the client #1:   
  *spoof/1/1_1_0_0_3.bmp   
  *spoof/1/1_1_0_1_4.bmp   
  *spoof/1/1_1_0_2_3.bmp   
  *spoof/1/1_1_0_3_3.bmp   
  *spoof/1/1_1_0_4_3.bmp   
  *spoof/1/1_1_0_5_3.bmp   

## Request
The SCUT-SFVD is publicly available (free of charge) to the research community.  
Unfortunately, due to privacy reasons, we cannot provide the database for commercial use.

Those interested in obtaining SCUT-SFVD should download [release agreement](https://github.com/BIP-Lab/SCUT--SFVD/blob/master/SCUT%20FV%20Presentation%20Attack%20Database%20Release%20Agreement.pdf), and send by email one signed and scanned copy to scutbip@outlook.com.

While reporting results using the SCUT-SFVD, please cite the following article:  
@inproceedings{  
  title={Finger Vein Presentation Attack Detection Using Total Variation Decomposition},  
  author={Xinwei Qiu, Wenxiong Kang, Senping Tian, Wei Jia, and Zhixing Huang},  
  booktitle={IEEE Transactions on Information Forensics and Security},  
  pages={13(2):465-77},  
  year={2018},  
}

## Contact
Qiu Xinwei  
Biometrics and Intelligence Perception Lab.  
College of Automation Science and Engineering  
South China University of Technology  
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641  
Qiu.xinwei@mail.scut.edu.cn  

Huang Zhixing  
Biometrics and Intelligence Perception Lab.  
College of Automation Science and Engineering  
South China University of Technology  
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641  
Huang.zhixing @mail.scut.edu.cn  

Prof. Kang Wenxiong  
Biometrics and Intelligence Perception Lab.  
College of Automation Science and Engineering  
South China University of Technology  
Wushan RD.,Tianhe District,Guangzhou,P.R.China,510641  
auwxkang@scut.edu.cn

### KSW_2022_Spring_Program


# ⚡2022 Purdue Postition Estimation of Drone Project by TEAM_K2S3⚡
<hr>

📑 *Project Title*
        
    The Postition Estimation of UAV Using Deep Learning Method with Vision and Audio

📅 *Project Period*

    04-17-2021(SUN) ~ 08-05-2021(FRI)

🧖🏻‍♀️ *Problem Statement*
    
    Recently, as the demand for delivery has increased, there has been a lot of discussion about services that effectively deliver to users.
	In this situation, research in drone delivery service is improved.
	In the case of drones, they are more environmentally friendly than other delivery methods.
	Moreover, drone delivery systems can figure out the wrong delivery problem the reason why algorithms operate them and there is no traffic jam.
	So consumers can receive delivery services quickly.
	However, if the demand for drone delivery services increases, much discussion will be needed about drone traffic.
	The biggest problem here is when a collision occurs between the drones being delivered.
	Since accidents between drones occur in the air, they can bring a relatively greater risk than accidents on land.

📖 *Considerations*

    🥕Software : Develop an algorithm that can estimate the position of UAV for sensing and avoiding in drone delivery system.
    
    🥕Hardware : Using camera and microphone which can detect and estimate the target drone cost-efficiently.


💡 *Novelty*

  1. High Accuracy and Cost-efficeint method of detecting drone and estimate the position for SAA(Semse amd Avoid)
     => According to previous studies, conventional drone detection technologies such as Radar or Lidar are expensive, so compare to the traditional method, cost-effective vision-based detection methods are mainly used.
	   However, in the case of vision, it is difficult to distinguish between flying objects such as birds and drones.
	   Hence, drone detection is possible more accurately by using the microphone as an additional detection method to check if the drone approaches.
    
	2. Use Multi-modal method with vision and audio
     => Most previous research in drone detection field only focused on single domain.
	   Not only research in the drone detection task, but also studies in position estimation of drone are only interested in single domain.
	   However, the studies about multi-modality are increased and be one of the hot topic.
	   In this point of view, we can conduct the experiment with only one domain and multi-domain.
	   It should be big novelty in drone detection task.
	 
	 
🏛 *System Overview*


![image](https://user-images.githubusercontent.com/33504843/170927729-a3bfd4de-40e5-49fd-85a2-631ee9921a8e.png)

    1. The visual and acoustic data are collected via camera and microphone.
    
    2. The pre-processing is conducted on visual and acoustic data.
    
    3. The pro-processed data is labeled with distance from detecting drone.
    
    4. Deep learning based method would be used for training model.
	
    5. The combination method using visual and acoustic method could be compared with only vision or acoustic method.
    
    6. It will be deployed in drone delivery service via API.

 
🖥️ *Environment Setting*

    ✔️Google Colaboratory
    
    ✔️Python version 3.10
    
    ✔️OpenCV CV2 2.4 
    
    ✔️MacBook Air 2021 M1
    
    ✔️DJI MAVIC 2 Pro
	
  	✔️EVO 2
	
	
👨‍👩‍👧‍👧 *Collaborator*
     
    👩‍💻Dongwhan Lee
       -Kyunghee Univeristy
       -Major in Software Convergence
       -derick_lee@khu.ac.kr
       
    👰🏻Yeongseo Kim
       -Sangmyung University
       -Major in Computer Science Engineering
       -201910787@sangmyung.kr
      
    👨🏻‍💻Juann Kim
       -Sangmyung University
       -Major in Computer Science Engineering
       -201920951@sangmyung.kr
       
    👩‍🚀Heeyeon Shin
       -Kyunghee University
       -Major in Computer Science Engineering and International Studies
       -567didi@khu.ac.kr
       
    👩‍🚀Yeeun Heo
       -Soongsil University
       -Major in Computer Science Engineering
       -gjdpdms2005@soongsil.ac.kr
       
    👨🏻‍Luke Siemers
       -Purdue Univeristy
       -Major in CNIT
       -lukesiemers33@gmail.com

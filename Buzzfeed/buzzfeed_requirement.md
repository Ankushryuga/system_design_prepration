## Question: Design a trendy news website like Buzzfeed.   
1. Functional Requirements:  
   1.1. Admins should be able to post stories that contain a mix text, photos, and videos.
   1.2. Users should be able to load the buzzfeed website and consume content on desktop and mobile. 

2. Nonfunctional Requirements:
   2.1. High availability during peak hours.
   2.2. Time to first byte < 200ms.   
   2.3. Data redundancy for stories for fault tolerance.   

3. Assumptions:
   3.1. 5% of stories account for 95% of traffic.   
   3.2. The average video is 10mb.   
   3.3. Each story has one video (10mb), one image(90kb) and text(2kb).   

4. Estimated Usage:
   4.1. 100 million month active users.   
   4.2. 15 stories published a day.   
   4.3. Usage peaks are 100* average.   
   

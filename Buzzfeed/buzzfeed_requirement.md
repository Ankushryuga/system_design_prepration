## Question: Design a trendy news website like Buzzfeed.   
1. Functional Requirements:   \n
   1.1. Admins should be able to post stories that contain a mix text, photos, and videos. \n
   1.2. Users should be able to load the buzzfeed website and consume content on desktop and mobile.   \n

2. Nonfunctional Requirements:
   2.1. High availability during peak hours.   \n
   2.2. Time to first byte < 200ms.   \n
   2.3. Data redundancy for stories for fault tolerance.   \n

3. Assumptions:
   3.1. 5% of stories account for 95% of traffic.   \n
   3.2. The average video is 10mb.   \n
   3.3. Each story has one video (10mb), one image(90kb) and text(2kb).   \n

4. Estimated Usage:
   4.1. 100 million month active users.   \n
   4.2. 15 stories published a day.   \n
   4.3. Usage peaks are 100* average.   \n
   

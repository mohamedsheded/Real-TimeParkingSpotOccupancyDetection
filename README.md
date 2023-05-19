# Real-TimeParkingSpotOccupancyDetection
•Implemented a classification model capable of analyzing images or video frames to determine if a parking spot is empty or not.
•Developed a utility script that utilizes the connected components function in OpenCV to detect the boundary boxes of parking spots. This step ensures precise identification and localization of each parking spot within the video.
•Calculated the similarity between the current and previous frames to detect changes. By comparing frames, I can identify any differences or alterations, such as the appearance or disappearance of a vehicle in a parking spot.
•Plotted histograms of the calculated frame differences to gain insights into their distributions By analyzing the distributions and characteristics of the frame differences, I established threshold values that enable real-time analysis while minimizing script complexity.
•Incorporated a text overlay on the video feed to display the number of occupied parking spots in real-time. This additional feature enhances the system's usability and provides immediate information to users

![Alt Text](https://drive.google.com/file/d/1sEZWpxCYA7n69NX_WnyVBFtaj1woWAby/view?usp=share_link)

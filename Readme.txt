2017.07.30

Dennis Im Created this project in my house.

For more cases, There is a camera (IP or WEBCAM) in fornt of LED Billboard.
Even though VA technology are invented, 
Still human operators in NOC are monitoring Digital Billboard on CCTV screen.

Now, I am supposed to make it automatic and genious.

Modules
1. Server
2. Client

User Scenarios
1. Setup Client
   - Connection with camera
   - Mapping image from camera with distortion
   - Server connection setting for downloading sets of registered video characteristics and for uploading display counts

2. Add video's characteristics in this server with vidoe's name
   - Save/register series of result of LBP or similar algorithm per each frame of original video content
   - Distribute new video meta to each clients 
 
3. Comparing in Client (Convolutional RNN)
   - Get video from camera
   - Make a result of LBP or similar algorithm per frame
   - Compare a series of metadata from original video contents with camera's data
   - Send result to the server
   * I'm supposed to use convolutional RNN algorithm.
   
4. Server can show result
   - count by medium, by video, by time
   - status dashboard in real time.


bomblim@naver.com

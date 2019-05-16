# video360player
panorama video player/360videoplayer/VR player/VR video


Description

 Video360player is a lightness and easy-to-use panoramic video player based on krpano engine that can be played in a HTML5 browser. If you want to insert panoramic video playback in your website or share panoramic video on social media, Video360player will give you great convenience and help.This player can be applied to the construction of professional panoramic VR/3DVR 360/180Degree video pc or mobile  website，And it can also be easily embedded in IOS or Android apps. 

Functions and advantages

Video360player can play different panoramic video by simple URL call, while setting up the initial angle of view, start time, and video type (supporting 3D 360/180Degree stereoscopic panoramic video type).The same url-address can support the playback of computer browsers and mobile device browsers, and our interface will be adaptive to browsers.At present, we offer two sets of UI options.Advanced version support makes it easy to add subtitles.
• URL parameters Usage --(Upload the player directory to your server) 
../index.html?path=videos_dir&url=filename&t=10&h_view=0&v_view=0&f_view=130&3d_view=0

◦ path:  Set the directory path where the video is played. The path does not have to be in the player directory, but it must be the directory under the same domain name of the player's home directory. 
◦ url:  Set the name of the video file to play. Note that the name must without playing the file suffix name (.Mp4). 
◦ t:  Set the start time of the video playback, the unit is seconds, and the 0 is to start from scratch. 
◦ h_view:  Setting the video default horizontal direction angle of view. (-180~180) 
◦ v_view:  Setting the video default vertical direction angle of view. (-90~90) 
◦ f_view:  Setting the video default field of view. (75~150) 
◦ 3d_view:  (Optional) Setting the video type.Choose General(normal) panoramic video or stereoscopic panoramic video type.
(0-General panoramic video; 1-Top to bottom; 2-Side by side) 
◦ text:  (Optional) Setting video subtitles type, default 0.
(0-Hide subtitles; 1-Vr subtitles; 2-Flat subtitles, suitable for iphone screens under 5 inches in VR model; 3-Desktop only)
Note: It is recommended to select VR headset which can adjust the pupil distance to start Flat subtitles in VR mode. 


• Subtitles add-on 
You can quickly add subtitles to each video through separate JSON files.
subtitle   


Examples
You can visit our example website examples page. 


More details

video360player 
For complete player information, please visit our website video360player.com. 

Note: Please note that a basic official krpano license is needed. 


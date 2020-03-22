## Inspiration
Security and facial recognition was our main interest when planning our project for this Makeathon. We were inspired by a documentary in which a male was convicted of murder by the police deparment in Los Angeles. The man was imprisoned for six months away from his daughter and wife. He was wrongfully convicted and this was discovered thorugh the means of a video that displayed evidence of him beign present at a LA Dodgers game at the same time of the alleged murder conviction. Thus, he was set free and this story truly impacted us from an emotional standpoint because the man had to pay a hefty price of six month prison time for no reason. This exposed us to the world of facial recognition and software that can help identify faces that are not explicitly shown. We wanted to employ software that would help identify faces based on neural networks that were preloaded.



## What it does

The webcam takes a picture of the user's face, and it compares it to preloaded images of the user's face from the database. The algorithm will then draw boxes around the user's face and eyes.


## How I built it

To build this project, we used a PYNQ board, a computer with an Ethernet cable, and several cables to power the PYNQ board as well as neural networks to power the technology to identify the faces (xml files), as well as Python programming to power the software. We used a microprocessor, ethernet cable, HDMI cable, and webcam to power the necessary devices for the PYNQ board. The Python programming coupled with the xml files that were trained to recognize different faces and eyes were used on a Jupyter platform to display the picture taken as well as boxes around the face and eyes.


## Challenges I ran into

We faced a plethora of problems while completing this project. These range from technical gaps in knowledge to hardware malfunctions that were unexpected by the team.

The first issue we ran into was being given an SD card for the PYNQ board that was not preloaded with the required information. This meant that we had to download a PYNQ file with 1.5 GB of data from the pynq.io. This would hinder our process as it could lead to future difficulties so we decided to switch the SD card with one that is preloaded. This lead us to lose valuable time trying to debug the PYNQ board. 

Another issue we had was the SD card was corrupted. This was because we unintentionally and ignorantly uploaded files to the Jupyter platform by clicking “Upload” and choosing the files from our personal computer. What we should have done was to use map networking to load the files from our personal computer to Jupyter successfully. Thus, we will be able to implement pictures for computer recognition.

Finally, the final issue we had was trying to import the face recognition API that was developed by the Massachusetts Institute of Technology. We did not know how to import the library for use, and given more time, we would explore that avenue more as this was our very first hackathon. We would export it in the PYNQ folder and not the data folder, which is a feature that was elaborated upon by the Xilinx representative.



## Accomplishments that I'm proud of
Loading code and images from our computers into the PYNQ board. We were also able to link a web camera with the board while also being able to analyse the pictures taken from the web camera.


## What I learned
As a team we were able to learn more about neural networks and how the PYNQ board technology could be incorporated into various areas including our intended purpose in security. To be specific, we learned how to use Jupyter and Python as tools to create these possible embedded systems and even got to explore ideas of possible machine learning.


## What's next for PYNQ EYE
Our project is able to recognize users using their facial features. With that being said, there is a huge application in the security industry. In instances where employees/workers have security recognize them and their id to enter the premise of the company, this technology could prove to be useful. The automation in the security aspect of facial recognition would allow employees to show their face to a camera and be granted access to the building/premise, removing the need for extra security detail and identification that could easily be falsified, making the security of the premise much safer. Another application would be home security where the facial recognition system would be used to disable home alarms by the faces of the residents of the property. Such applications prove that this project has the potential to boost security in the workforce and at home.


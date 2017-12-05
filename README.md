# Max-Midterm
Ben Greenfeld Patch 

Description
The function of my patch invloves visuals reacting to audio. By pulling in the audio file included on GitHub to the source, the data is then split into two paths. Path 1 analyzes the spikes of the audio track and feeds that data into a color picker and subsiquently the preview. Path 2 feeds the audio into an audio splitter then into a pattern mapper. With the feeds from path 1 and 2 the result is a visuals display of shapes and colors reacting to the audio.

Ben's Role: Developer

Patch Reviewer: Maddeline Vose

  Notes / To Do List:
  
1)	Add a description to your max patch in the read me section of Github (COMPLETED)
2)	Add what externals you need to your max patch in the read me section of your Github (COMPLETED)
    a.	Extenals like osculator or soundflower
3)	Add descriptions on your internal patch to describe what is going on 
4)	Look at who your audience is for your patch, by saying “change threshold dynamically based on incoming amplitude” .You should reword it so anyone with a fifth grade education would understand what your were talking about 
5)	The patternmappr is an interesting feature of the patch you should put a description to the audience to move the toggles up and down to change the image. 
6)	For the (onebang,delay, and number object) in the patch, change the description to a common term such as FPS instead of “minimum time between each attack”. 
7)	Explain the bpatcher object, and the source.
    a.	This is a keyfeature of your patch and needs to be explained in a very simple way like this is what allows for the sound to enter into Max/Msp. 
8)	Explain the ezdac~ object in max 
    a.	Basically works as an on or off button for your patch. 
    b.	Insert a comment saying to click here.
    c.	Anything with a ~ in max is audio

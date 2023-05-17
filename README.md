# Modern-Professional-Website-Template
This Is a template for those that want a modern look to a professional website.

Directions:

1st you want to go ahead and download the files by clicking on file download as zip

2nd you want to unzip those and have them all in one file/directory preferably on desktop to make things easier

3rd double click the Index.html file that should bring you to the website on chrome (or another browser). You should notice that most of the stuff has insert here. You may also notice the boxes are quite small dont worry about that as you fill in information they will correct

How to edit the Website:

! To See Results Ctrl+s/save and refresh the page !

* open the .html file in a text editor or preferably vscode (open in notepad by going to notepad and open file)

* you will now notice lines of html for now do not touch anything that doesnt have some sort of insert here. Only edit what is inside the <> </> do not touch the arrows or whats inside them only what is in between <> </> 

* you notice a '<h2 class="About">About Me</h2>' and below that a '<p>Insert-Here</p>' in between those '<p>' you will start to put your about me. I would recommend pressing enter so that they are spaced like this '''<p> /newline </p>''' (new line just like hitting enter on mc word you would see a blank line)

* Now below that you will see the '<h2 class="skils">Skills:</h2>' and below that you will see '<li> insert here </li>' just like before put your skills in those. If you need to delete a bullet point delete the '<li> </li>' and everything between it. If else do the opposite. This is a list by bullet points just like a resume I would recommend keeping it that way, however if you would like to change it to sentence for some reason delete the '<ul> </ul>' and everything between it. Replace with '<p> </p>' and like before put what you need to inbetween those.

* next find the '<div class="onetomanyboxe">' and ignore the name of the class? now find whats inside those href="-insert-here-" And insert the link to your professional links like github or linkedin. Make sure it is inside the qoutations. Next to that you will see the Insert-link-name this is just what the link name will be show as when people look at the website so keep it short like github for a link to your github.

* Last but not least is the imag for your profile pic. thats what that weird oval shape will be when it gets an image. So go up to the top and look for '<img src="rando.jpg">' thats where you img will go. There are a few parameters to this so be careful, first the image has to be in the folder that evrything else is in or you have to provide a path so /user/images/me.jpeg for example i would recomend putting in the folder so you can just put m.jpeg inbetween the qoutations. Also be aware that you may have to crop your photo accordingly. Mainly applies to phone cameras since the image is longer than the width, the circle will fit to image size and it will automatically fit into the oval. it will NOT automatically crop your image to look nice and pretty inside the circle. You dont want to end up like rando.jpeg who looks slighlty strectched.


How Do I edit the colors:

* I would not recommend doing this but im not a graphic designer so what do i know

* This is where the CSS file comes in. Open that as well (same method as before)

* I have provided colors in a txt file you will need to find anything that says background-color: or color: and edit what comes after, I cant provide as much direction as i did with the html so your on your own just play around with colors and ill give you a few tips

* Tips: Try not to edit the background color of the body this has an animation set to it if you ae going to change it i would recommend going down to the bottom where it says :root and edit the colors in that to change the colors of the background. Once more I would recommend going to coloors website to look at gradients you like then copy the hex colors and replace them down in the :root. BE AWARE THAT YOU MAY ACCIDENTALLY DELETE A ; OR A , AFTER A COLOR IF YOU DO THIS THE WEBSITE WILL BREAK SO IT WILL BE OBVIOUS. Once again to see the results Ctrl+s and refresh the page 

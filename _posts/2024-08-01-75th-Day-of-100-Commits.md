## 75th Day! 

Today I'm focused on figuring out my button-click-to-add-field challenge in my app. By searching "javascript how to add an input to the page with a button click" I found (an example of what I want)[https://www.geeksforgeeks.org/how-to-add-an-input-field-on-button-click-in-javascript/] at (geeksforgeeks.org)[https://www.geeksforgeeks.org/]-for now, I'm abandoning my idea of User input determining the number of fields because that appears to be more complicated and I would benefit more from gaining a little momentum. 

I copied and pasted what I needed from their snippet and edited my element IDs, but it did not work. So I'm creating a local only repo to test their entire code to identify where mine is going wrong.

1- Copied and pasted their whole code into my index.html and went live-worked.
2- Created a separate script file and cut & pasted the script code from index-worked.
3- Commented out all of my main.js and pasted their script code. Added their div to my customenewseq.html-worked.
4- Changed their words to mine-worked.
5- Pasted my input fields-did not work.
6- Commented out my div-did not work. I can see when I click my Add a Pose button, it wants to add their input fields in their div. I think it's because my main.js still matches theirs...
7- Edited main.js to be my names-did not work, but I can see it trying to add mine but they disappear immediately.
8- Commented out my Pose Number fieldset-did not work, same results as above.
9- Noticed I still had G4G code test in my customnewseq.html. Commented it out-IT WORKS!!! 

Up next: adjust input so it won't accept floats. Clean up my code. Add create custom sequence button on index.
Eventually: add functionality to remove a pose. Style. Add timer...

As I was cleaning up my code, I noticed my JavaScript is relying on the div stuff in brown. Not exactly sure why, but it may have something to do with how the function is written.

Also my input fields, even though they are set to min=0 and step=1, are allowing manually-entered negative and decimal numbers, in spite of what all the answers report to questions like "How do I limit input to positive integers?" From my brief search, there appears to be consensus that as long as you do what I did, negative floats will be denied. That method will limit what the up/down arrows on the input box allow, but a user can type a minus sign and/or a decimal point. I did find this article https://www.tutorialspoint.com/how-to-allow-only-positive-numbers-in-the-input-number-type which recommended adding to the input: onkeypress="return (event.charCode !=8 && event.charCode ==0 || (event.charCode >= 48 && event.charCode <= 57))", which does work to limit the manual input to positive integers, yay! Then I noticed the max number can still be violated manually, boo. MDN says yeah, users will be able to input whatever, but it will be returned as invalid-if MDN doesn't think I should worry about it, I won't, but I do have a voice inside wanting to make it the way I imagine it should be!

Outside of programming, but influencing my low mood today is a relentless heat wave which includes wildfires in some of my favorite places. Loneliness continues to gnaw at me. But I had some major victories today-75 days is a milestone, and I made concrete progress on my app. I also remembered a song that I've been trying to think of since last night-it's been ages since I've played it, and I just started singing it as I worked, which makes me feel grateful for a good brain... Not that THC is that bad, not even sure if it is any bad, but I think I will let my med card lapse. I can get it again if I change my mind. 


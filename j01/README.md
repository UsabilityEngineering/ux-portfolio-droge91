# ux-portfolio-droge91
## Using Quasar for mod installation
I enjoy playing Super Smash Bros Ultimate on my pc using an emulator called Ryujinx.  Playing on an emulator naturally allows for greater control and customization, but anyone who has actually tried to install mods on an emulator can tell you that doing so is a daunting task.  
This is where Quasar comes in, Quasar is an application capable of installing modifications for you once provided the path to your emulator's folder.  Here you can see the applications home screen
![Quasar home screen](/assets/Quasar_home)

As with most mod installers it works by integrating with the mod distribution website pertaining to its game, in this case Gamebanana.  This is an example of **Consistency and standards**, a usability guideline that states that applications should follow industry standards so that users are not confused. Shown below is Gamebanana's Quasar integration.

![gamebanana integration](/assets/Quasar_integration)

Having found a mod that I wished to install I clicked 1-click install to prompt quasar to begin downloading the mod
As I had expected Quasar immediately begin showing a download progress bar, providing **visibility of system status** by letting me know that me clicking install had actually done something, and giving me an approximate measure of how long the download would take.  
![Quasar Download](/assets/Quasar_down)
Having installed a mod I immediately loaded the game to test if it had worked only to surprised that the mod had not had any effect.  I had a **mental model** that it would install mods one by one but the **conceptual model** was that of batch installation.  The program expects you to download all of the mods that you wish to install before clicking the start transfer button to install them all at once.
Once I figured this out I clicked start transfer.  Doing so pulled up a transfer status screen as shown below.
![Transfer status](/assets/quasar_transfer)
Everything appeared to have worked however when I loaded the game I was again greeted to a lack of the modifications I had thought I just installed. A quick check of the settings informed my that my file transfer path was set incorrectly so it had simply dumped the files in my AppData folder.  I was able to **recover from the error** by correcting the file transfer path, and once I did I was able to successfully install my desired mod.  But the **Error Prevention** of the application could be improved by simply indicating in the tranfer status section that the path specified does not match the expected structure.

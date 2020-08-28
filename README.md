# GSoC(2020) Project for Internet Archive

Being a part of **GSoC 2020** gave me an opportunity to be involved in enhancing the features of the Wayback Machine's browser extension. I am deeply grateful to my mentors [Mark Graham](https://github.com/markjgraham) (mark@archive.org) and [Anish Kumar Sarangi](https://github.com/anishsarangi) (anish.kumar.sarangi@gmail.com) for letting me be a part of the Internet Archive community and guiding me throughout the program. I would also like to express my sincere gratitude to [Carl Gorringe](https://github.com/cgorringe) (carl@gorringe.org) for his generous support and guidance throughout the summer.

## Project Description:

In this project, I contributed along with the Internet Archive developers in order to continue the development of the Wayback Machine's Chrome extension, which was later enhanced to support various other browsers including Firefox, Edge, Safari, and Brave.
The project is divided into 5 features, each having a different utility such that the people interested in researching the web may find useful. All of the following 5 features have been merged to the [Internet Archive's Wayback Machine Chrome repository](https://github.com/internetarchive/wayback-machine-chrome):

### 1. Enhanced the existing Search Box feature:

This enhancement/feature allows the user to enter a URL in the Search Box and enables the extension features to work on this URL, without needing the user to open it in a new tab/window. The user can simply enter a URL in the Search (input) Box and operate the extension features on this URL.


### 2. Added 'Fact Check' feature:

Integrated the [our.news](https://our.news/) fact check API with the Wayback Machine extension. Added the auto-detection checkbox option in the settings menu that, when checked, automatically detects the availability of fact checks and displays the **'F'** icon in the toolbar and shows a purple **'Fact Check'** button in the extension if fact checks are available. And allows the user to see the available fact checks in a tab/window. The users who like to check the authenticity of the information displayed on the websites may find this feature helpful.


### 3. Added 'Bulk Save' feature:

This is a powerful feature that enables the user to create a list of URLs and save all those URLs together, without needing to save each URL separately. This feature also allows the user to save the bookmarks by importing from the browser and adding to the list. The user is also given the freedom to delete URL(s) from the list which is/are not intended to be saved.


### 4. Re-defined the display of existing Contexts:

Initially, all the context features were displayed in a single tab/window which was opened by a single 'Show Contexts' button. This was re-defined to add a new button for each context and display each context feature on a separate tab/window.
This allows the user to specifically select only the context(s) that he/she wants to see.


### 5. More enhancements:

The following were performed throughout the program (some of these were based on user feedback and resulted in an improved user experience):

- Solved the existing issues to ensure full functionality
- UI improvements
- Searched, inspected and fixed bugs
- Code improvements


## Other Features:

These are the features that were implemented during the summer but were not merged due to being not required:

### 1. Add Link Sharing and Email Sharing buttons in the share section:

These features are additions to the share section and enable the user to share the opened page/URL through email sharing and/or link sharing.


### 2. Add a button to share the extension:

This feature enables the user to share the link to the browser's extension store page from where the Wayback Machine extension can be downloaded. This was developed in order to ensure that the users share and download the original extension developed by the Internet Archive.


## Credits

- Richard Caceres [@rchrd2](https://github.com/rchrd2)
- Rakesh Naga Chinta [@rakesh-chinta](https://github.com/rakesh-chinta)
- Abhishek Das [@abhidas17695](https://github.com/abhidas17695)
- Mark Graham [@markjgraham](https://github.com/markjgraham)
- Benjamin Mandel [@BenjaminMandel](https://github.com/BenjaminMandel)
- Anton Shiryaev [@Eagle19243](https://github.com/Eagle19243)
- Kumar Yogesh [@kumarjyogesh](https://github.com/kumarjyogesh)
- Vangelis Banos [@vbanos](https://github.com/vbanos)
- Kerry Rodden [@kerryrodden](https://github.com/kerryrodden)
- Max Reinisch [@MaxReinisch](https://github.com/maxreinisch)
- Anish Kumar Sarangi [@anishsarangi](https://github.com/anishsarangi)
- Pushkit Kapoor [@tikhsuP](https://github.com/tikhsuP)
- Carl Gorringe [@cgorringe](https://github.com/cgorringe)


## License

Copyright © 2017-2020 Internet Archive. All rights reserved.

Licensed under the terms of the [GNU Affero General Public License version 3 (AGPLv3)](LICENSE).

<p align="center">
  <img src="https://github.com/tikhsuP/GSoC-2020-Project/blob/master/webextension/images/logo.gif" width="300px">
</p>

# GSoC(2020) Project for Internet Archive

Being a part of **GSoC 2020** gave me an opportunity to be involved in enhancing the features of the Wayback Machine's browser extension. I am deeply grateful to my mentors [Mark Graham](https://github.com/markjgraham) (mark@archive.org) and [Anish Kumar Sarangi](https://github.com/anishsarangi) (anish.kumar.sarangi@gmail.com) for letting me be a part of the Internet Archive community and guiding me throughout the program. I would also like to express my sincere gratitude to [Carl Gorringe](https://github.com/cgorringe) (carlg@archive.org) for his generous support and guidance throughout the summer.

## Project Description:

In this project, I contributed along with the Internet Archive developers in order to continue the development of the Wayback Machine's Chrome extension, which was later enhanced to support various other browsers including Firefox, Edge, Safari, and Brave.
The project is divided into 5 features, each having a different utility such that the people interested in researching the web may find useful. All of the following 5 features have been merged to the [Internet Archive's Wayback Machine Chrome repository](https://github.com/internetarchive/wayback-machine-chrome):

### 1. Enhanced the existing Search Box feature ([#607](https://github.com/internetarchive/wayback-machine-chrome/pull/607)):

This enhancement/feature allows the user to enter a URL in the Search Box and enables the extension features to work on this URL, without needing the user to open it in a new tab/window. The user can simply enter a URL in the Search (input) Box and operate the extension features on this URL.

<p align="center">
  <img src="https://github.com/tikhsuP/GSoC-2020-Project/blob/master/webextension/images/UseSearchURL.png" width="300px">
</p>


### 2. Added 'Fact Check' feature ([#631](https://github.com/internetarchive/wayback-machine-chrome/pull/631)):

Integrated the [our.news](https://our.news/) fact check API with the Wayback Machine extension. Added the auto-detection checkbox option in the settings menu that, when checked, automatically detects the availability of fact checks and displays the **'F'** icon in the toolbar and shows a purple **'Fact Check'** button in the extension if fact checks are available. And allows the user to see the available fact checks in a tab/window. The users who like to check the authenticity of the information displayed on the websites may find this feature helpful.

<p align="center">
  <img src="https://github.com/tikhsuP/GSoC-2020-Project/blob/master/webextension/images/toolbar/toolbar-icon-F64.png" width="64px">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://github.com/tikhsuP/GSoC-2020-Project/blob/master/webextension/images/fact-check.png" width="300px">
</p>

### 3. Added 'Bulk Save' feature ([#624](https://github.com/internetarchive/wayback-machine-chrome/pull/624)):

This is a powerful feature that enables the user to create a list of URLs and save all those URLs together, without needing to save each URL separately. This feature also allows the user to save the bookmarks by importing from the browser and adding to the list. The user is also given the freedom to delete URL(s) from the list which is/are not intended to be saved.


### 4. Re-defined the display of existing Contexts ([#651](https://github.com/internetarchive/wayback-machine-chrome/pull/651)):

Initially, all the context features were displayed in a single tab/window which was opened by a single 'Show Contexts' button. This was re-defined to add a new button for each context and display each context feature on a separate tab/window.
This allows the user to specifically select only the context(s) that he/she wants to see.


### 5. More enhancements:

The following were performed throughout the program (some of these were based on user feedback and resulted in an improved user experience):

- **Solved the existing issues to ensure full functionality:**

    Auto adjust tab width ([#557](https://github.com/internetarchive/wayback-machine-chrome/pull/557))

    Show error message on empty Context screen ([#555](https://github.com/internetarchive/wayback-machine-chrome/pull/555))

    Fix 'Show Contexts' button bugs ([#550](https://github.com/internetarchive/wayback-machine-chrome/pull/550))

    Set Tabs to be Opened in Context Page ([#539](https://github.com/internetarchive/wayback-machine-chrome/pull/539))

    Fix Saving Messages [#533](https://github.com/internetarchive/wayback-machine-chrome/pull/533))
    
    Reopen same context tab on reload ([#515](https://github.com/internetarchive/wayback-machine-chrome/pull/515))

- **UI improvements:**

    Re-design Context Page ([#593](https://github.com/internetarchive/wayback-machine-chrome/pull/593))

    Animate SPN ([#633](https://github.com/internetarchive/wayback-machine-chrome/pull/633))

    Tweak "Bulk Save" CSS ([#660](https://github.com/internetarchive/wayback-machine-chrome/pull/660))

    Move 'Auto-Update Contexts' to 'Context' menu ([#637](https://github.com/internetarchive/wayback-machine-chrome/pull/637))

    Context Screen bugs ([#640](https://github.com/internetarchive/wayback-machine-chrome/pull/640))

    Dim SPN button ([#652](https://github.com/internetarchive/wayback-machine-chrome/pull/652))

    Modfied Scrollbar in Contexts Page ([#502](https://github.com/internetarchive/wayback-machine-chrome/pull/502))

    Improve the content representation in Annotations Screen ([#501](https://github.com/internetarchive/wayback-machine-chrome/pull/501))

    Make Welcome Page Responsive ([#492](https://github.com/internetarchive/wayback-machine-chrome/pull/492))

    Improve the switch UI in Settings menu ([#489](https://github.com/internetarchive/wayback-machine-chrome/pull/489))

- **Searched, inspected and fixed bugs:**

    Exclude UP & DOWN keys from event ([#625](https://github.com/internetarchive/wayback-machine-chrome/pull/625))

    Remove max-height of popup ([#634](https://github.com/internetarchive/wayback-machine-chrome/pull/634))

    Don't show count on web.archive.org pages ([#636](https://github.com/internetarchive/wayback-machine-chrome/pull/636))

    Check login status on Excluded URLs ([#653](https://github.com/internetarchive/wayback-machine-chrome/pull/653))

    Handle error for TV News Clips ([#656](https://github.com/internetarchive/wayback-machine-chrome/pull/656))

    Improve working of Social Share section ([#584](https://github.com/internetarchive/wayback-machine-chrome/pull/584))

    Open Feedback URL Depending on Browser ([#572](https://github.com/internetarchive/wayback-machine-chrome/pull/572))

- **Code improvements:**
    
    Adjust styles and rewrite code according to STYLE GUIDE ([#598](https://github.com/internetarchive/wayback-machine-chrome/pull/598))

    Change storage to local and Use arrow functions ([#579](https://github.com/internetarchive/wayback-machine-chrome/pull/579))

    Remove code that is not needed ([#568](https://github.com/internetarchive/wayback-machine-chrome/pull/568))

- **Write Tests:**

    Add test for 'makeValidURL()' ([#609](https://github.com/internetarchive/wayback-machine-chrome/pull/609))

- **Add support for Edge:**

    Updates to support in Microsoft Edge ([#608](https://github.com/internetarchive/wayback-machine-chrome/pull/608))

    Add API for Edge ([#626](https://github.com/internetarchive/wayback-machine-chrome/pull/626))


## Other Features:

These are the features that were implemented during the summer but were not merged due to being not required:

### 1. Add Link Sharing and Email Sharing buttons in the share section ([#527](https://github.com/internetarchive/wayback-machine-chrome/pull/527)):

These features are additions to the share section and enable the user to share the opened page/URL through email sharing and/or link sharing.
<p align="center">
  <img src="https://github.com/tikhsuP/GSoC-2020-Project/blob/master/webextension/images/sharing.png" width="300px">
</p>


### 2. Add a button to share the extension ([#509](https://github.com/internetarchive/wayback-machine-chrome/pull/509)):

This feature enables the user to share the link to the browser's extension store page from where the Wayback Machine extension can be downloaded. This was developed in order to ensure that the users share and download the original extension developed by the Internet Archive.

<p align="center">
  <img src="https://github.com/tikhsuP/GSoC-2020-Project/blob/master/webextension/images/share.png" width="300px">
</p>


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
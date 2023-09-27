<a name="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li><a href="#video-demo">Video Demo</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

<div align="center">
<img src="images/product_screenShort1.jpg" alt="Logo" width="320" height="390" style="border-radius: 10px;">
</div>

This is my detail description about MusicApp project when i am working at my company. Because of policy and privacy, i can not attach the code to this repository. If yout want to make some features like this application, please contact me at <a href="#contact">Contact</a>. 

MusicApp can play music both online and offline. Offline music refers to video or audio imported from `Google Drive, Box Drive`,... Online music is sourced from YouTube using `youtube/v1` API and `WKWebView` to obtain the actual MP4 link.
Music APP have some features:
- Import video and audio from Google Drive, Box Drive.
- Search video, audio.
- Create Playlists.
- Develop layout HomeController.
- Develop PlayerController: 
  - Replay Modes, Random Mode, Rate Media Mode.
  - Next, back video and audio.
  - Rewind or fast-forward media.
  - Convert media offline.
  - Download video Youtube.
  - Like musics.

Some frameworks and techniques:
- **Realm and FileManager**: : To save, manage and handle data (musics and playlists).
- **AVFoundation**: For playing musics.
- **DispathQueue and DispathGroup**: Fetching Data with multiple Threads.
- **UIview.animate(), CGAffineTransform(), UIPanGestureRecognizer()**: Enhancing user experiences.
- **URLSession**: For fetch RestAPI and download musics.
- **FFmpeg**: For converting music.
- **BoxSD and GGDriveSDK**: For importing musics.
- **WKWebView and Javascript**: Get actual video mp4 link.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

# Video Demo

# I. Import

Main Feature ProfileController

- Import music from `GoogleDrive` and `BoxDrive` :

| Google Drive | Box Drive |
| :--------: | :--------: | 
| <img src="gif/bottomSheetAndLogout.gif" alt="Logo" height="100%" style="border-radius: 10px;"> | <img src="gif/editProfile.gif" alt="Logo" width="100%" style="border-radius: 10px;"> | ![](gif/follow.gif?cropResize=50,50) |


# II. HomeController

- In HomeController, i just implement layout and AlbumsDeTailVC

| Main Home | Albums Detail |
| :--------: | :--------: | 
| <img src="gif/dynamicCell.gif" alt="Logo" height="100%" style="border-radius: 10px;"> | <img src="gif/anotherUser.gif" alt="Logo" height="50%" style="border-radius: 10px;"> | 


# III. Search Controller

- Searching with pure music, filter music, video and music local. I also implement load more and no search again when switch filter>

# IV. UploadStatusController
Upload Status with caption and photo image.
<div align="center">
<img src="gif/UploadTus.gif" alt="Logo" width="200" height="440" style="border-radius: 10px;">
</div>

## Contact

Full Name - [Trinh Tien Viet](https://www.facebook.com/mdgarp49) - tienviet153153@gmail.com

Project Link: [https://github.com/Vietdz123/Instagram.git](https://github.com/Vietdz123/Instagram.git)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
1
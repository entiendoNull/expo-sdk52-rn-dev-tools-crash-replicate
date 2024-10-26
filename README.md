### Just to demonstrate an error

Opening React Navigation dev tools on Expo SDK52 makes the app crash immidietely. 

I discovered this first on a real app that I upgraded to SDK52 beta.

I made a completely new project with SDK52 to verify this behavior, and it persists. I've tried the same thing on a new SDK51 project, where it works.

Steps to reproduce
- Created a development build (I ran it on my iOS simulator)
- shift+m in the terminal, selecting `Open dev-plugins/react-navigation`
![cli-selection](https://github.com/user-attachments/assets/7f554e6b-0c63-4ef9-8f3e-90ec90f8ceb6)
- the app crashes

  

https://github.com/user-attachments/assets/ffb05f30-babb-4235-a8e9-5741b5fe05a0

# Low-Fi Prototype Report

<br/>

## Problem Statement

Many people love sports. Watching live sports in the stadium makes audiences feel excited and sense of belonging. But due to the COVID-19 pandemic, sports fans cannot go to the stadium.

So they feel less excited and can’t enjoy such a passionate atmosphere of the stadium. Thus, many people are craving for interaction with other people while watching sports game.

<br/>

## Tasks

- Use characters and interfaces such as emoticon and chatting to help people’s interaction
- Archiving important moments during the livestream game based on the number of people’s response and sharing the moments with other people
- Provide mini events that people can play by groups of teams that can encourage competition

<br/>

## Prototype

### Link to prototype & Instructions
Please watch these links and video!
- Prototype Link
    
    [https://www.figma.com/proto/kiofUh9BV0Qyi5pjfavubR/Cheers-low-fi-prototype?node-id=0%3A1&scaling=min-zoom&starting-point-node-id=2%3A2025&show-proto-sidebar=1](https://www.figma.com/proto/kiofUh9BV0Qyi5pjfavubR/Cheers-low-fi-prototype?node-id=0%3A1&scaling=min-zoom&starting-point-node-id=2%3A2025&show-proto-sidebar=1)
    
- Video with Instructions about the prototype
    
    [https://youtu.be/QUNfzzH-c7k](https://youtu.be/QUNfzzH-c7k)
    
- Video with figma prototype demo
    
    [https://www.youtube.com/watch?v=pC37Qc-Yug0](https://www.youtube.com/watch?v=pC37Qc-Yug0)

<br/>
    
### Prototyping Tool

We use “Figma” to make a low-fi prototype. Because Figma is more familiar with our team and it is easy to cooperate with teams. It applies presentation functions so we can show our prototype by an end-to-end flow. Also, it shows the css properties of each element which are helpful for us to develop “Cheers.” By locating frames in chronological and functional order, we describe story lines and similar functions easily. Figma supports basic figure and designing tools so we can describe major scenes like the main page, administrator page, mini-game scene, etc. It is well to make prototype presentations by interacting with each frame or element. Sadly, it is hard to express the dynamic functions such as moving characters, playing mini-games, etc.

<br/>

### Design Choice

- Ovarall
    - Real-time moving function of characters
    - Real-time baseball game video
    - Real-time chatting and expression of emotion
    - Real-time mini game
    - Playing the cheering song of winner team
    - Playing the archived moment of the game

We’ve excluded every real-time function and playing the video or cheering song. These functions are not appropriate to implement in a low-fi prototype, because the tool we used could only show static states or interaction between two static states. We decided to alternatively show how these will work as a paused screen. Also, the screenshot of the baseball game on the screen is a random screenshot of a baseball game between Hanwha and Samsung.

Also, we depicted 20 users in the prototype, due to two reasons: First, we focused on showing a single user’s end-to-end experience, which does not require the number of other users to be many. Second, to prepare for practical coding of this service, we limited the number of synchronous users to 100. 20 or so users will be enough to represent the user interactions. This is explained in more detail in the **Observations** section.

- **Task 1**
    - We did not show all of the user’s IDs on the main screen. Instead, we only showed one user’s ID. This is because this is a low-fi prototype, and showing the idea and focusing on the main character that our supposed user is using is more important.

- **Task 2**
    - We did not show the process of the video being achieved when the number of clicks from the users were over a certain threshold. This was because it was hard to show that many people clicked at the same time through the low-fi prototype. We only showed the notice when the video was archived.
    - We did not implement the thumbnail of actual videos in the toggle list of archived videos. Instead, we replaced it with random screenshots of baseball games.

- **Task 3**
    - We did not show all of the steps as the two games progressed, because we thought that giving the idea of how the game worked was more important than showing all the repetitive and detailed steps of the game.

<br/>

### Representative Screenshots

1. **Introduction**
- Select Sports game which user wants to watch
    - You can scroll down and view what game is going on
    - If the game has already started, the score of each team, game progress, and total number of people participating is shown.
    - We limited the maximum number of participants for each team, to prevent excessive congestion of the crowds. Also, we are planning to implement the minimum capacity as well, to enable minigame (task 3) more easily.
    - If the game is yet to start, you can see the starting time of the game and the total number of people participating.

[https://lh6.googleusercontent.com/KJ1fVeARiCAjs9HYUQqOoFZGKL2nfSZm15-KuArX-diDvt55HW1LtMBdJq9TFCstOWv_KyyCOj_kcFCtzW86F0Ybumn4oPUxbxLSmgOBgfAMeIifX8MDbp7DJlfqMIu6niG6SVnw=s0](https://lh6.googleusercontent.com/KJ1fVeARiCAjs9HYUQqOoFZGKL2nfSZm15-KuArX-diDvt55HW1LtMBdJq9TFCstOWv_KyyCOj_kcFCtzW86F0Ybumn4oPUxbxLSmgOBgfAMeIifX8MDbp7DJlfqMIu6niG6SVnw=s0)

<br/>

2. **Task 1**
- Choose a character
    - there are total 4 kinds of characters that each team member drew
    - We are thinking about unifying the general design of the characters, but we also think that showing four different identities is interesting. This is part of our plan for improvement.
    - You can choose the team, and the color of the cloth changes depending on the team.

[https://lh6.googleusercontent.com/3UUsKMvg7I8qbVfxvnGDwQIAEZkQs6A34maMVlJzpmWBbPBMn-CQU703Re6WyFP_Z43cmFWCZGC8Nv578f3SwIGyu7gEj1ue0Mf6U672M115HLK0YHG84wC_hB890th4yOcmhhyu=s0](https://lh6.googleusercontent.com/3UUsKMvg7I8qbVfxvnGDwQIAEZkQs6A34maMVlJzpmWBbPBMn-CQU703Re6WyFP_Z43cmFWCZGC8Nv578f3SwIGyu7gEj1ue0Mf6U672M115HLK0YHG84wC_hB890th4yOcmhhyu=s0)

[https://lh3.googleusercontent.com/QWCzTxxgqC-rXulBgdMlouCRWO_pJ0l36bAzSzJIUeHfUh_MUXOvCkkNoJRJVRLaL6NvNwxrjgNYhbPPv4jA4IAlmZ7mg6ncvMjvNJIyHBgxLuPW0nt4eVEZ0TpLCND1tWhjvd08=s0](https://lh3.googleusercontent.com/QWCzTxxgqC-rXulBgdMlouCRWO_pJ0l36bAzSzJIUeHfUh_MUXOvCkkNoJRJVRLaL6NvNwxrjgNYhbPPv4jA4IAlmZ7mg6ncvMjvNJIyHBgxLuPW0nt4eVEZ0TpLCND1tWhjvd08=s0)

- On the main page, sers can interact with others by emoticons and chatting.
    - The user’s character is highlighted, so that the user can spot his own character easily.
    - The emoticons and chatting boxes are implemented as a toggle box.
    - We focused on showing the characters, and thought that chatting and emoticon tool boxes should be small enough to not to disturb the interaction.
    - However, there was feedback that the tool boxes were too small, and we are considering increasing the size.
    - Users can show their agreement or excitement by pressing the cheer button on the lower left corner, and your pose turns into a hooray pose.

[https://lh4.googleusercontent.com/pLuX_cY-whGA1snVU_UyWwda52aqYw3aVDHiuHJ1fyWjr88Yj0jBOj31IJ90rhAdfmljxiYEzdYO8QXKuwVJ7zug4RO32_7nF-RG4VKmbsyekitx0WsdZ9P64eZ1B5T5ZH5gWuTw=s0](https://lh4.googleusercontent.com/pLuX_cY-whGA1snVU_UyWwda52aqYw3aVDHiuHJ1fyWjr88Yj0jBOj31IJ90rhAdfmljxiYEzdYO8QXKuwVJ7zug4RO32_7nF-RG4VKmbsyekitx0WsdZ9P64eZ1B5T5ZH5gWuTw=s0)

[https://lh3.googleusercontent.com/hOkVRtMNU78j6uIt241keSWyd5Q_H-6T_BXJFV1weAm_f4tOvRJWEbhvWP_8UHh_5G60eL7-6hvm7oOZy1hqMeH7XAOmq4IZ468-55IE5Vbi87AQVxvnr5JxjH_Fm2-MPtNSAnu2=s0](https://lh3.googleusercontent.com/hOkVRtMNU78j6uIt241keSWyd5Q_H-6T_BXJFV1weAm_f4tOvRJWEbhvWP_8UHh_5G60eL7-6hvm7oOZy1hqMeH7XAOmq4IZ468-55IE5Vbi87AQVxvnr5JxjH_Fm2-MPtNSAnu2=s0)

[https://lh4.googleusercontent.com/2hlyw1uagG5eSgD_OnYZePI1d83txT9VtSKq5Cconrsci_8adYY_ep48WsMor97JAmOFD6q1BMxZ_WF5pcZkNfO1bfffMQZgAlAaVA0LKlf25tauOfzHOlonffN08M0HZ3qB0n5_=s0](https://lh4.googleusercontent.com/2hlyw1uagG5eSgD_OnYZePI1d83txT9VtSKq5Cconrsci_8adYY_ep48WsMor97JAmOFD6q1BMxZ_WF5pcZkNfO1bfffMQZgAlAaVA0LKlf25tauOfzHOlonffN08M0HZ3qB0n5_=s0)

<br/>

3. **Task 2**
- Archiving important moments during the livestream game based on the number of cheers that the people clicked
    - When a certain number of people have pressed the “cheer” button on the lower left side for a certain period of time (measured in seconds), the moment is archived.
    - The archived list of moments are shown as a toggle on the left upper corner of the main screen
    - If the user clicks the thumbnail of the archived video, the video is shown as a short pop up.
    - The length of each moment will not be very long, although the maximum time length is not yet fixed (we will discuss with our team members)

[https://lh4.googleusercontent.com/uEsI0V45-A6ubAsSc0gnUhZ8FYEULcWQX4oh9Gu-aIS3J18qtAhYoN0d5IRNrejEP9qBdLJkyEGjG1vykk6pTT4OCghi5EPKbXPGPYd20AGYhh8yLw8KT_MDgfVi1344uolBdk2B=s0](https://lh4.googleusercontent.com/uEsI0V45-A6ubAsSc0gnUhZ8FYEULcWQX4oh9Gu-aIS3J18qtAhYoN0d5IRNrejEP9qBdLJkyEGjG1vykk6pTT4OCghi5EPKbXPGPYd20AGYhh8yLw8KT_MDgfVi1344uolBdk2B=s0)

<br/>

4. **Task 3**
- We announce the start of the minigame in advance, and also count down 5, 4, 3, .. . Detailed UI can be found in the link.
- After the countdown, we will reposition all the users automatically so that they will be aligned as a team on two sides of the screen.
- When the number of participants of two teams are different, we are considering to align them as best as we can. To improve this part, we will employ the maximum / minimum number of participants for each team. This is part of our plan for further implementation.
- We erased all the interaction related toggles, such as the “view” button for task 2 or the emoticon + chatting box in task 1. This is because we wanted the users to concentrate on the game.
- The prize after winning the game is still in discussion. Originally, we were aiming to play the song of the team that won. We are still discussing what can be a good motivating prize for the winning team.

[https://lh3.googleusercontent.com/nzvr8zlUi9E8NtLGvQvn5Pjsu_L0qODBUtSv1Mg2Y9zwSax80jR-2k4iJAxcDLnDS-6dt6wtg3nW6bcm41ZVqsXckihB5nr_H6ZKtdWYFLT3R0RKEMa_mGKJUpyme3xKaNj5_xnk=s0](https://lh3.googleusercontent.com/nzvr8zlUi9E8NtLGvQvn5Pjsu_L0qODBUtSv1Mg2Y9zwSax80jR-2k4iJAxcDLnDS-6dt6wtg3nW6bcm41ZVqsXckihB5nr_H6ZKtdWYFLT3R0RKEMa_mGKJUpyme3xKaNj5_xnk=s0)

- Mini Game 1: Pushing a space bar
    - Pushing the space bar has the same effect as pushing the cheer button explained on task 1.
    - The team that presses the most number of spacebar wins, and as the number of spacebar pressed increases, the bar on both sides of the screen increases. This UI is purely to encourage users and add more fun.

[https://lh5.googleusercontent.com/LI-xkNrcux0EK2jDSvPx0_djSE5QHC6GWNWbSz_h1Js74wV64m-aeso51o4kQjbhhqXrUhpi5ImUY0B2w9_Az5bWwmxrdhRdi5aNxiG7MPGxZBwMb4qxs3vvoZK007VaDM7hLbsC=s0](https://lh5.googleusercontent.com/LI-xkNrcux0EK2jDSvPx0_djSE5QHC6GWNWbSz_h1Js74wV64m-aeso51o4kQjbhhqXrUhpi5ImUY0B2w9_Az5bWwmxrdhRdi5aNxiG7MPGxZBwMb4qxs3vvoZK007VaDM7hLbsC=s0)

[https://lh5.googleusercontent.com/bHi6QYPq8AdEYpbvFYKEP6FLC_05bq6DBPSqcyWVmsAAMsjZEz3lHLl_p8rMwUzZiLlg6EQHyoIAewRtCvctOOhhq3lzzIfE-zJCGwhGSiT13q1SWakP9Jz20g327hxY8QHv9pDg=s0](https://lh5.googleusercontent.com/bHi6QYPq8AdEYpbvFYKEP6FLC_05bq6DBPSqcyWVmsAAMsjZEz3lHLl_p8rMwUzZiLlg6EQHyoIAewRtCvctOOhhq3lzzIfE-zJCGwhGSiT13q1SWakP9Jz20g327hxY8QHv9pDg=s0)

- Mini Game 2: Doing the waves
    - This is a game where users press the “cheer” button in sync with the timing. It is a famous game in korea, called “파도타기"
    - There was feedback about the timing of pressing the spacebar. We were thinking of showing a translucent color bar to indicate the people playing the game.

[https://lh6.googleusercontent.com/qsb9-fKYB0-_3yMdppoCiBQbAsXP6e5ZSLSmXvKK4WLyLGjTN8gGzN80SpdhRj4ViLuK-YIVkYiwy-_l7fQQbX6FrV2wlIOww4ZY-YB9NXwKmUQwkGQeYaweA8M6_MHZvAqXMy0J=s0](https://lh6.googleusercontent.com/qsb9-fKYB0-_3yMdppoCiBQbAsXP6e5ZSLSmXvKK4WLyLGjTN8gGzN80SpdhRj4ViLuK-YIVkYiwy-_l7fQQbX6FrV2wlIOww4ZY-YB9NXwKmUQwkGQeYaweA8M6_MHZvAqXMy0J=s0)

<br/>

5. **Administrator Page**

We need an administrator for quality control of users and to carry out the game.

The user should enter a passcode before joining as administrator. The passcode identifies which game the administrator belongs to, and enables the user to have authority of administrator to only the identified game.

[https://lh3.googleusercontent.com/AKZfyzqWR9nshIQeN-DjlPsaS67lBS8608bb-J46_QE3TfYz3UA-Is2fpMcmafUbxT2DYtJx53uNz4ULBpKCdIDuFcIsyPfZeJbniA2LE_lDQoxW5HKoOR2nVJ_yqN8KMggivcr6=s0](https://lh3.googleusercontent.com/AKZfyzqWR9nshIQeN-DjlPsaS67lBS8608bb-J46_QE3TfYz3UA-Is2fpMcmafUbxT2DYtJx53uNz4ULBpKCdIDuFcIsyPfZeJbniA2LE_lDQoxW5HKoOR2nVJ_yqN8KMggivcr6=s0)


[https://lh3.googleusercontent.com/GXZ-hRzQbfD4wr8kK0-cwNsgHJ_uUqBI4xg5kL6UbdLuOgcJ3T78jleX-ilupaQ70C8hYAGdAakmeiOq7-zE1PSadfcMdiJRYWRQ9QNQKiFblOhfLerVpR5iEfmDm0hSWtOsfQZH=s0](https://lh3.googleusercontent.com/GXZ-hRzQbfD4wr8kK0-cwNsgHJ_uUqBI4xg5kL6UbdLuOgcJ3T78jleX-ilupaQ70C8hYAGdAakmeiOq7-zE1PSadfcMdiJRYWRQ9QNQKiFblOhfLerVpR5iEfmDm0hSWtOsfQZH=s0)

- The administrator can monitor the user’s main page.
- The administrator can also see the chatting screen and monitor the users
- If there is an emergency, the administrator can use the “send a notice” chatbox to send messages to the user.
- The administrator can also exit inappropriate users.
- There was feedback that one administrator could not monitor all the users alone, so if other users could also report inappropriate users to the administrator, it would be helpful. It is one of our plans for future implementation.
- The administrator selects the game to start the game. Then, notice for the start of the game and countdown explained in task 2 is automatically done. We decided to implement the sequence of the game so that the administrator has the least to do.
- The administrator can see the progress of the game and how much time is left through the progress bar on the lower middle part of the screen. This is because the games are mostly automatically progressed.
- If there are not enough people to play the game (especially game 2: 파도타기), than the game button cannot be selected (disable the button function)

[https://lh4.googleusercontent.com/6bKO6WWlrZANrMFS7o3WsoBO_Js7e75EkWMGdwtLui_CH9Rra661vwx8M2rIAXDcPXacL8f0L7ZOlt2z0krdLOudEX7kd5EyU4Qfv13AN_Tc43MfxZ8aLowgOZLWEu6V0gZLlcgu=s0](https://lh4.googleusercontent.com/6bKO6WWlrZANrMFS7o3WsoBO_Js7e75EkWMGdwtLui_CH9Rra661vwx8M2rIAXDcPXacL8f0L7ZOlt2z0krdLOudEX7kd5EyU4Qfv13AN_Tc43MfxZ8aLowgOZLWEu6V0gZLlcgu=s0)

- send a notice to the users

[https://lh4.googleusercontent.com/2C5Lai5W03wWLt7oI5z-AGucXkvEqp-jMwPvyha9ZUyLtQIHqqGL4btSRlGabZ-iKhhvOIwrrgeNMv2YIpxT1B288BRAyYN4XMIzDZ0R8pa2nFy-4J8pf-fXHtINvSSIamIUWrXx=s0](https://lh4.googleusercontent.com/2C5Lai5W03wWLt7oI5z-AGucXkvEqp-jMwPvyha9ZUyLtQIHqqGL4btSRlGabZ-iKhhvOIwrrgeNMv2YIpxT1B288BRAyYN4XMIzDZ0R8pa2nFy-4J8pf-fXHtINvSSIamIUWrXx=s0)

[https://lh6.googleusercontent.com/HGhwhvjX8xxxyMnkPLDf0iQOeO6EznQwRfTVzSB0iCQ80qlnD_45D1WpppshwP4BvDYE6HegmP8XDwvesKxp32_hXTYqIgs38RFyGYlXs_Ao-JnfjCG5bnuHRrwbBf8Tg6Hv0u3o=s0](https://lh6.googleusercontent.com/HGhwhvjX8xxxyMnkPLDf0iQOeO6EznQwRfTVzSB0iCQ80qlnD_45D1WpppshwP4BvDYE6HegmP8XDwvesKxp32_hXTYqIgs38RFyGYlXs_Ao-JnfjCG5bnuHRrwbBf8Tg6Hv0u3o=s0)

<br/>

## Observation

<br/>

### Instructions

The following are the instructions and demo link & videos that we gave out to our testers.

- We made two videos for instructions.
- Basically, when you test our prototype, please click the screen(we don’t recommend you to click the next slide button below the screen) then it will show which button you should click or it will show the next step.
- Video that shows only the prototype without explanation : [https://www.youtube.com/watch?v=4uFioEnzVyw](https://www.youtube.com/watch?v=4uFioEnzVyw)
- Video includes explanation : [https://www.youtube.com/watch?v=2QcHYhin1q0](https://www.youtube.com/watch?v=2QcHYhin1q0)

<br/>

### Participants

**Pn: age, department, position, info related with baseball**

P1 : 24, Computer engineering, B.S., no interest

P2 : 22, English Literature, B.S., no interest

P3 : 24, Electrical Engineering, M.S., no interest

P4 : 23, Computer engineering, B.S., no interest

P5 : 23, Business administration, B.S.

P6 : 23, Aerospace engineering, B.S., no interest

P7 : 22, Industrial engineering, B.S., little interest

P8 : 27, Informations security, M.S., little interest

P9 : 23, Chemical and Bio molecular engineering, B.S.

P10 : 23, Mechanical engineering, B.S.

<br/>

### High level task or theme

We classified our feedback with 3 high-level criterias.

**Task**

- Task 1
    
    Use characters and interfaces such as emoticon and chatting
    
- Task 2
    
     Archiving important viewpoints during the livestream game based on the number of people’s likes
    
- Task 3
    
    Play Mini-Game with other people such as wave surfing(파도타기) or clicking competition based on teams.
    
- Overall
    
    that are not included in task 1, 2, 3
    

**Type**

- Functionality
- UI

**How Critical**

- High
- Medium
- Low

<br/>

### Feedback

[**Task 1]**

- **High**
1. I wish I could distinguish my character from Cheers. (P1, P4, P8)(UI)

=> We will change the UI of the character so that the user can see his own character with unique effects such as a halo or square box that is distinguishable.

<br/>

- **Medium**
1. I wish we could filter the chatting by team. For example, when there are teams A and B, I want to have a filtering function so that I can only see chatting from team A.(P8) (UI)

=> We will enable the filtering function to show only one team’s chat.

2. I think there are many cases where I want to express emotion quickly (such as angry expression), and it would be nice to add shortcut keys so that I can express them immediately (P4) (func)

=> We will make the shortcut key for emotion expression, and write this in a tutorial.

3. I hope the character design is a unified design.(P2)(UI)

=> We will design the characters in a unified style, but with different designs

<br/>

- **Low**
1. I think the chat window is small. I wish it was as big as one third of the monitor (P10) (UI)

=> We will try to use the function of controlling the size of chatting windows. However, through many discussions, we thought that the chatting window should not be too big, because showing character UI was more close to our core idea of interaction.

2. I hope the UI of speech balloons seen after chatting will be more specified.I wonder how long the speech balloons will stay valid once it is shown. (P3) (UI)

=> We will decide the time limit to show the speech bubble. We are thinking of about 5 seconds.

3. I hope you can see the speech bubble right away instead only after the mouse has hovered.(P5) (UI)

=> We have considered this, but thought that the UI of showing it right away may become too handful when there were many users chatting at the same time. That is why we replaced the chatting content shown over the character with a speech bubble emoticon.

<br/>

[**Task 2]**

- **High**
1. The criteria for counting cheers to archive important moments during the game is not clear. It needs to be specified whether it is necessary to press at the exact same moment or aggregate pressing over a certain period of time.

=> We will catch the moment when the number of cheers is over a certain figure during 20 seconds, and represent the timeline with the point that is exactly the middle point of those 20 seconds.

<br/>

- **Medium**
1. I hope that scenes that individuals want to own can also be saved, aside from videos that many people wanted to save.(P3)(func)

=> We have discussed adding moments when individual users want it, and showing it in the timeline like a heatmap. However, we are worried that when there are many users, there may be too many moments that each user wants to save, which can cause confusion. We will consider this feedback, and further discuss whether it is valid feedback.

<br/>

[**Task 3]**

- **High**
1. It may be hard to get the timing right at mini-game “Surfing the waves(파도타기)”(P4)(func)

=> We will add the color expression or countdown for timing while playing the game “surfing the waves”.

2. I wish there was a tutorial which explained how to use “Cheers” and the function of “cheers”, especially in the mini-games.(P1, P6, P7)(UI)

=> We will add the tutorial which the user can see at the first time and a tutorial button which the user can see anytime.

<br/>

- **Medium**
1. When the user cheers (pushes a space bar), I wish the user can see additional effects like sparkle, because making ‘hooray’ poses doesn’t seem enough. (P3)(UI)

=> We will implement a more distinguishable effect for cheering.

2. I hope that the number of people cheering for each team can be shown. If the number of people in one team is far greater, it will help to understand the situation when playing mini-games.(P6)(func)

=> We will add an expression of the user's number on the header.

3. I hope we can listen to the cheering BGM individually, not only after the mini game.P5) (func)

=> We thought of the cheering BGM after the mini-game as a prize, so if we implement the UI that can play songs any time the user wants, the meaning of the prize might fade. We are considering taking this feedback and changing the prize of the mini-game to something else.

<br/>

- **Low**
1. I think it'd be nice if you put in a big speech bubble that says “start” like a real game in the mini game UI.(P7) (UI)

=> We will implement the start notation as the feedback just before the start of the mini games.

2. The mini-game count of 5 seconds seems too short. It'll be nice if a notice is displayed at the corner a minute before the start of the mini game, and see the count properly 10 seconds before. (P9)(func)

=> We will try to notify the start of the mini-game earlier.

<br/>

[**Overall]**

- **High**
1. Since it seems difficult for only the administrator to manage all the users, I hope there is a function that allows users to report other users that are not appropriate.(P2)(func)

=> We will implement the report function for users, so that users can notify the administrator if there is a user that is acting inappropriately.

2. I want to add a function that allows you to watch only videos when you don't want to watch the characters so that you can focus only on the game.(P2)(UI)

=> Getting the characters not shown may contradict with the core idea of our service, which is supporting interactions between watchers. However, we will consider this feedback, because we also think that users may have similar needs as this feedback.

<br/>

- **Medium**
1. If there are many users, there is a concern about buffering the broadcast video. It seems that the timing of cheering may be different because the Internet sync is not right for each user.(P9)(func)

=> We will try to solve this problem but this is a matter of external functionality, so it may not be solved. We do feel that this feedback is important, because live stream and real-time functions are the main part of our service.

<br/>

- **Low**
1. It would be nice if the background image ui feels like an actual baseball stadium audience.(P5, P6, P10)(UI)

=> We will add some background themes which the user can choose. We are trying to find the background that goes well with the character design and other UIs.

<br/>

### Overall plan for improvement summary

**For task 1,**

There are two main tasks: character design and chatting (speech bubble) function.

For character design, 

We will change the UI of the character so that the user can see his own character with unique effects such as a halo or square box that is distinguishable, and make a shortcut key for emotion expression. Also, we will re-design the characters in a unified style.

For chatting function,

We will enable the filtering function so that the user can see only one team’s chat by choice. Also, we will put in the function of controlling the size of chatting windows. However, through many discussions, we thought that the chatting window should not be too big, because showing character UI was more close to our core idea of interaction.

For speech bubbles,

We have to decide how much time the speech bubble will be shown after the user has chatted. We will only show the picture of the speech bubbles on top of the character instead of all the contents, because showing all the contents of the speech bubble may become too much when there are many users chatting at the same time.

<br/>

**For task 2,**

We will catch the moment when the number of cheers is over a certain figure during 20 seconds, and represent the timeline with the point that is exactly the middle point of those 20 seconds.

We have also discussed adding moments when individual users want it, and showing it in the timeline like a heatmap. However, we are worried that when there are many users, there may be too many moments that each user wants to save, which can cause confusion. We will consider this feedback, and further discuss whether it is valid feedback.

<br/>

**For task 3,**

We need to give a more detailed explanation of the timing of the game and when the game will start, to reduce the confusion of the users.

We will add the tutorial which the user can see at the first time and a tutorial button which the user can see anytime, and give out notifications several minutes before the mini game starts, so that the user will not be confused. We will also add a color expression or countdown for timing during “surfing the waves(파도타기)” and implement a more distinguishable effect for cheering. We will add an expression of the user's number on the header so that when there are different numbers of users in the two teams, users can understand the situation more clearly.

<br/>

**Overall**,

We need to implement the report function for users, so that users can notify the administrator if there is a user that is acting inappropriately. Also, adding some background themes which the user can choose will also provide better UI.

**Most of all, we got the feedback of whether our service will be presentable with many users.** Especially, when we test our service through real testers, there are two problems:

1. How many testers are we going to use?
2. If there are many testers, does the interactions between users maintainable technically?

These depend on how many users we aim to target with our service. On the low-fi prototype, we set the maximum user as 100, and 50 for each team. We are thinking of possible solutions as below:

1. Ask as many people as possible, so that each team member can bring at least 5 testers. This guarantees at least 20 testers.
2. Replicate each tester to 5 characters. This makes the illusion of 100 testers. The replicated characters will move in sync.

This is not the accurate user experience, but we will be able to predict what it will be like if there were many users. As for the second question, we limited the maximum number of participants to 100 in this prototype so that we can practically control the crowd during the minigame. Ideally, it would be better to have as many users as possible. However, 100 is the number that we thought was possible in a practical sense and at the same time is big enough to depict the purpose of our service.

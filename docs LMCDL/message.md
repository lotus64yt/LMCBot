# !Message

## Basic usage
```!message Hello World !```<br>
```+channel channelId``` <br><br>
![image](https://github.com/lotus64yt/LMCBot/assets/114228798/001030a0-12a1-4b56-a6ca-d9be5b06b641)



## With custom embed
```!message```<br>
```+channel channelId```<br>
```+content Some content```<br>
```+title Some title```<br>
```+description Some description```<br>
```+footer Some footer```<br><br>
![image](https://github.com/lotus64yt/LMCBot/assets/114228798/716e9093-9405-4c7e-b9f0-a8a00fd9efa9)



## Custom usage
```!message Hello World!```<br>
```+reactions ⚠️```<br><br>
![image](https://github.com/lotus64yt/LMCBot/assets/114228798/2d29cb84-3537-4f70-bbf1-698e5ff46503)

* Note : You can put more than one emoji.
  ```+reactions ⚠️👋```



## Error
- ```Title lenght must be less than 256 character (279)```
  This error say that you can't have a title bigger than 256 caracters here 279.
  The embed will be sended but the title will be cut and you will have an error message.

- ```Description lenght must be less than 4096 character (5012)```
  This error say that you can't have a description bigger than 4096 caracters here 5012.
  The embed will be sended but the description will be cut and you will have an error message.

- ```Footer lenght must be less than 256 character (279)```
  This error say that you can't have a footer bigger than 256 caracters here 279.
  The embed will be sended but the footer will be cut and you will have an error message.

- ```Cannot send an empty message.```
  This error say that you want to send an empty message.

# Singo_Bingo
Meilyn Massie Senior Project 

A game inspired by Jackbox TV and Bingo. Each player will connect to a host device (laptop or smart TV) with their own personal device. On each personal device a bingo card will generated. It will be full of songs instead of the standard cells such as B2. Each bingo card is generated through Spotify API. You can pick any Spotify playlist you want, and it will generate the cards with the song titles based on which playlist you pick. It will also use the API to play the music for about 15 seconds to give you time to guess the song. In addition you will get 5 seconds of silence for any after thoughts. First to get bingo win!

This game is currently only single player. Multiplayer will be implemented later. There are many bugs to find and squash.

STEPS TO START GAME: 

1. Have a Spotify Premium account 
2. Find a playlist you want to play the game with and grab the playlist ID
3. Go to client > src > components > GenerateBingoCard.js > input Spotify playlist where it says playlistID
4. Go to terminal and cd to client 
5. Run
6.   npm install
7.   npm run build
8.   npm run start
10. Open localhost link provided in console
11. Go to test tab and input the playlist ID
12. Go to Bingo Card tab and refresh the window. The cards should now have songs on them
13. Go back to test tab and repeat step 7. Make sure music is playing 
14. Switch back to Bingo Card tab and enjoy the game!

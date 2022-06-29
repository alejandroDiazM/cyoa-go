# CHOOSE YOUR OWN ADVENTURE

Template for a "Choose your own adventure" game written in Go. The app reads a JSON file with all the story options and renders it through an HTML template on the server, making the user able to read and play.

<br>

## Usage

After cloning the repo, go to the directory and run:

```
go mod init cyoa 
```
This initializes the cyoa module so main.go can import its functions. A go.mod file will be created in the directory. With that done, run:

```
go run main/main.go
```
The app will be served to http://localhost:3000, allowing you to play the CYOA game.

If you want to add branches or change the story, just edit the .json file accordingly. Remember to update the dependencies on the program if you change the name of the file or the JSON fields.

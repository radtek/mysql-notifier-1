# mysql-notifier
Notification area (task bar) icon to display the status of one or more MySQL databases (live, dead)

## Installation
As a command line app
```
go get github.com/SC7639/mysql-notifier
```

As a gui less app (no cmd / terminal window for windows. Will add linux and mac commands in the future)
```
git clone https://github.com/SC7639/mysql-notifier.git
cd mysql-notifier
go build -ldflags -H=windowsgui -o mysql-notifier.exe main.go functionality.go
```
## Example
If all of the mysql database are live the icon (outlined in red)
![alt text](https://github.com/sc7639/images/readme-all-live.png "All Live")

If one of the mysql databases goes down (outlined in red)
![alt text](https://github.com/sc7639/images/readme-dead.png "All Live")
# servermedia
ServerMedia

### Create file main.go

```
package main

import (
	"https://github.com/iperfex-team/servermedia"
)

func main() {

	servermedia.Start("/audio")

}
```

### Build or Run

```
go mod init servermedia
go get -v
go build -o servermedia
chmod 777 servermedia
./servermedia
#go run main.go
```

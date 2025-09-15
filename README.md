# mturncat

```console
git clone https://github.com/TheKeniya/mturncat<br>
cd mturncat<br>
go build -o turncat cmd/turncat/main.go<br>
./turncat --verbose -u <username> -p <username> 'udp://127.0.0.1:5555' "turn://1:1@<TURN-IP>:<TURN-PORT>?transport=udp" 'udp://X.X.X.X:XXXX'<br>
```
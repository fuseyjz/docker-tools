# capa by FireEye
- docker build -t capa .
- docker run -ti --cap-drop ALL -v /path/to/binary:/malware capa suspicious.exe

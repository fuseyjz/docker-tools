# capa by FireEye
- docker build -t capa .
- docker run -ti --cap-drop ALL -v /path/to/docs:/malware capa suspicious.exe

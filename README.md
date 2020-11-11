Forked from https://github.com/alexeygrigorev/vimeo-download

## tl;dr

```
brew install ffmpeg
pip3 install -r requirements.txt
```

```
python3 vimeo-download.py --url "http://...master.json?base64_init=1" --output <optional_name>
```

```
ffmpeg -i v.mp4 -i a.mp3 -map 0:v -map 1:a -c:v copy -c:a copy output.mp4 -y
```

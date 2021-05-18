# Support Local Artists - Generate software to rack up listens on streaming platforms

```python
import spotify
import time


def main(song: str):
    song = spotify.song(song)

    while song.listenCount < 1000000000:  # to the moon we go
        song.play()
        time.sleep(30)  # stream count iterates after 30 secs.

if __name__ == "__main__":
    main()

```

# How to join video files using `ffmpeg`

First, create a `files.txt` using the following format:

```
file 'file1.mp4'
file 'file2.mp4'
file 'file3.mp4'
```

And then, execute the following on your terminal:

```shell
ffmpeg -f concat -safe 0 -i files.txt -c copy output.mp4
```

ffmpeg will read every `file` entry on `files.txt` and concatenate them into `output.mp4`

Want to put comments? Just use `# your comment here`. Every line starting with `#` is ignore by `ffmpeg`

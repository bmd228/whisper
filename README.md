For CPU:

```sh
docker run -d -p 9000:9000 -e ASR_MODEL=base whisper:cpu
```

For GPU:

```sh
docker run -d --gpus all -p 9000:9000 -e ASR_MODEL=base whisper:gpu
```


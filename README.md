# guix channel

The following definition goes into ~/.config/guix/channels.scm

```
(cons (channel
        (name 'mklntf)
        (url "https://github.com/mklntf/guix-channel.git")
        (branch "main"))
      %default-channels)
```

Afterwards `guix pull` and `guix install test-hello` should work.

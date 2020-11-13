# Extract auto-generated Youtube subtitles

* Use Google2SRT

# Generate English base translation file

`sub2po` is part of the `translate-toolkit` ubuntu package

```
sub2po -P subs2.srt -o subs.pot
```

# Generate translated subtitles

```
po2sub -t subs.srt es.po es.srt
```

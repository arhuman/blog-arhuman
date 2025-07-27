
## Basic operations

### list draft

hugo list drafts

### Optimize images (requires ImageMagick)

```
convert -quality 75 image.jpg image.jpg2
mv image.jpg2 image.jpg # If ls -al confirms that all went well
```

```
convert -resize 960x image.jpg image.jpg2
mv image.jpg2 image.jpg # If ls -al confirms that all went well
```

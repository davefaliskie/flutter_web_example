# Flutter Web Example

Flutter project configured for deployment on the web through GitHub Pages and a custom domain.

[See this repo for actual hosted project](https://github.com/davefaliskie/flutter-website)

### Deploying on Web

```
make deploy-web
```

### Watch The Video

[![Watch the video](https://img.youtube.com/vi/iOra0bxlWdE/maxresdefault.jpg)](https://youtu.be/iOra0bxlWdE)

# Fix Image Issues With Flutter Web

### Watch The Video

[![Watch the video](https://img.youtube.com/vi/X8UR4PCukqA/maxresdefault.jpg)](https://youtu.be/X8UR4PCukqA)

### CORS Settings For AWS S3

```
[
    {
        "AllowedHeaders": [
            "*"
        ],
        "AllowedMethods": [
            "GET",
            "HEAD"
        ],
        "AllowedOrigins": [
            "http://localhost*",
            "https://YOUR_CUSTOM_DOMAIN.com"
        ,]
        "ExposeHeaders": [],
        "MaxAgeSeconds": 3000
    }
]
```

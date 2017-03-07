# docker-ionic

Docker image to build ionic 2

# Usage

When you build a project you need to specify a platform, otherwise it tries to build for iOS as well.
```
docker --rm -v [directory-ionic-project]:/data/ ttonline/ionic ionic build [www|android]
```

You can run npm (or yarn) install as well
```
docker --rm -v [directory-ionic-project]:/data/ ttonline/ionic npm install
```

###### Based on image setup from [netizy](https://github.com/netizy/docker-ionic-2)
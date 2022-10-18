# Annotation Store

This repo is used as a data store for Label Studio.

Start Label Studio on PC:

```bash
docker run -it -p 8080:8080 -e EXPERIMENTAL_FEATURES=1 -v `pwd`/data/label-studio:/label-studio/data heartexlabs/label-studio:latest
```

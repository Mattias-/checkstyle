## Checkstyle

Read more at:
http://checkstyle.sourceforge.net/

## Usage

The [Sun](https://github.com/checkstyle/checkstyle/blob/master/src/main/resources/sun_checks.xml) and [Google](https://github.com/checkstyle/checkstyle/blob/master/src/main/resources/google_checks.xml) checkstyle files are already in the image located at the root.
```
docker run --rm -v "$PWD":/src mattias/checkstyle -c /sun_checks.xml /src
```

How to package the ardrone_pilot extension with your application:

```
make_apk.py --package=org.xwalk.extensions.ardrone \
--extensions="./out/Default/gen/ardrone_pilot/" \
--arch=x86 \
--manifest="./examples/ardrone_pilot/manifest.json"
```

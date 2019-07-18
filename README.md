# clover-pipeline-code-coverage
Simple tool to process clover code coverage report &amp; exit with error to trigger pipeline failure if coverage doesn't match minimum required coverage



Pipeline example usage:

```
wget https://example.com/cloverpipeline
cloverpipeline --file clover.xml --mincov 65
```

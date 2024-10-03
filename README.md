Demonstrate an issue specifying output name with generated figures



``` bash
quarto render demo/demo.qmd --output new_demo.html --output-dir _site/
```

``` bash
quarto render demo/demo.qmd --output new_demo.html --output-dir _site/new_demo
```


``` bash

Quarto 1.5.57
[✓] Checking versions of quarto binary dependencies...
      Pandoc version 3.2.0: OK
      Dart Sass version 1.70.0: OK
      Deno version 1.41.0: OK
      Typst version 0.11.0: OK
[✓] Checking versions of quarto dependencies......OK
[✓] Checking Quarto installation......OK
      Version: 1.5.57
      Path: /opt/quarto/bin

[✓] Checking tools....................OK
      TinyTeX: (not installed)
      Chromium: (not installed)

[✓] Checking LaTeX....................OK
      Using: Installation From Path
      Path: /usr/bin
      Version: 2019

[✓] Checking basic markdown render....OK

[✓] Checking Python 3 installation....OK
      Version: 3.12.1
      Path: /home/apn/temp/output-name-test/venv/bin/python3
      Jupyter: 5.7.2
      Kernels: python3

[✓] Checking Jupyter engine render....OK

[✓] Checking R installation...........(None)

      Unable to locate an installed version of R.
      Install R from https://cloud.r-project.org/

```

# Jmm Package Test Runnner for Travis

This is a test runner for [Jmm](https://github.com/jminusminus/jmm) packages that are being run in [Travis](https://travis-ci.org/).

To test your package create a `.travis.yml` file using the following configuration.

```yaml
language: java
script:
  - git clone https://github.com/jminusminus/jmmtravis.git ~/.jmmtravis
  - ~/.jmmtravis/stage
os:
  - linux
  - osx
```

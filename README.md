This is the source code and output of my resume. Originally forked from https://github.com/sb2nov/resume.

### Build using Docker

```shell script
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex kevin_aiken_resume.tex
```

### Build directly on Linux
First, follow this guide to install the pre-reqs: https://gist.github.com/rain1024/98dd5e2c6c8c28f9ea9d

Then run

```shell script
pdflatex kevin_aiken_resume.tex
```

This will output a PDF.

### Build on Mac
```shell script
brew cask install mactex
```
Press `cmd+t` to reset the terminal session.

```shell script
pdflatex kevin_aiken_resume.tex
```

This will output a PDF.

### License

MIT License
This is the source code and output of my resume. Originally forked from 

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sourabh_bajaj_resume.tex
```

### Build directly on Linux
First, follow this guide to install the pre-reqs: https://gist.github.com/rain1024/98dd5e2c6c8c28f9ea9d

Then run

```shell script
pdflatex kevin_aiken_resume.tex
```

This will output a PDF.
### License

MIT License
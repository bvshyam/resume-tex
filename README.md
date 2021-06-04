A single-page, one-column resume for software developers. It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. The different sections are clearly documented and custom commands are used to provide consistent formatting. The three main sections in the resume are education, experience, and projects.


### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sourabh_bajaj_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)


### Steps
1. Goto Cocalc.com
2. Use Shyam_Resume.tex
3. Run below commands

docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex Shyam_Resume.tex

4. Done

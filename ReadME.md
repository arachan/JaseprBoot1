JasperReportBoot
==============

This Program make PDF View Form JRXML template.
This is Spring Boot Program.
So, execute any where and nothing Servlet Container.

Gradle Build Version

## How to execute

1. Git Clone to STS(Spring Tools Suite)
2. build it and run on STS.
3. Access http://localhost:8080/
4. show index.html and click link.
5. show PDF.

## Font Extensions
This program include font extensions.
I set Japanese font,IPAex Mincho (Serif) and IPAex Gothic (SanSerif).
So, This make PDF file include Japanese Font.

## Any JRXML template make PDF
For example
1. test.jrxml file add to src/main/resouces/jasperreports  
2. build and run
3. browser access to http://localhost:8080/pdf/test 
4. view PDF from test.jrxml

## Prarameter

make RequestParam.

I add no and date parameter.

## License

Apache License 2.0

[![Known Vulnerabilities](https://snyk.io/test/github/arachan/JasperReportBoot/badge.svg?targetFile=build.gradle)](https://snyk.io/test/github/arachan/JasperReportBoot?targetFile=build.gradle)

# ![Logo](media/favicon.png)

# Project architecture document.

- Review the [Architecture Diagram](architecture/README.md).
- Folder design information of the application.

```
.
+-- build                           '	Executable version of the project.
+-- docs						    '	Project, documents.
+-- reports                         '	Project, coverage, test, screen.
|   +-- coverage                    '	Project, coverage web content
|   |   ?-- index.html              '	Project, coverage report static file
|   +-- document                    '	Project, document web content.
|   |   ?-- index.html              '	Project, document report static file
|   +-- tests                       '	Project, test and coverage result.
|   |   +-- cobertura-coverage.xml  '	Project, coverage result.
|   |   +-- junit.xml               '	Project, Unit test result.
|   +-- screen                      '	Project, e2e screens.
+-- src							    '	Project resource files.
|   ?-- api					        '	In-app services.
|   ?-- assets			            '	Design assets.
|   ?-- controllers	                '	The parts that separate the business logic of the application and the user interface.
|   ?-- core					    '	Application core.
|   ?-- models					    '	View objects that separate the Controller From the user interface.
|   ?-- views					    '	The area users view with models.
+-- tests                           '	Project testing.
|   +-- e2e						    '	End-to-end test.
|   +-- unit					    '	Unit test.
|   +-- integration                 '	Integration testing.
+-- .editor.config                  '	Developers will use these code indents and styles in their IDEs.
+-- .env                            '	each env. the file holds or separates the development environment definitions.
+-- docker-compose.yml              '	each .yml file holds or separates runtime definitions.
+-- dockerfile                      '	each docker file prepares the runtime launcher image.

```

# Project development architecture

```
tests:?
testsResult:?
coverage:?
document:?
pretier:?
linter:?
stage:?
version:?
environment:?
```

## Environment

```
.env
.env.production
.env.development
.env.test
```

## Project Install

Install detail

```shell
$ install
▀ ╢█████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░╟
$ $CMD_INSTALL
```

### Test / Development / Production

Start Linter

```shell
▀ ╢█████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░╟
$ $CMD_LINTER
```

Start Prettier

```shell
▀ ╢█████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░╟
$ $CMD_PRETTIER
```

Start Test and Generate test report

xml [ ./reports/tests/junit.xml ]

```shell
▀ ╢█████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░╟
$ $CMD_TEST
```

Start Coverage and Generate coverage report

html [ ./reports/coverage ]

xml [ ./reports/test/cobertura-coverage.xml ]

```shell
▀ ╢█████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░╟
$ $CMD_COVERAGE
```

Generate Document

html [ ./reports/document ]

```shell
▀ ╢█████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░╟
$ $CMD_DOCUMENT
```

Build

binary [ ./build ]

```shell
▀ ╢█████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░╟
$ $CMD_BUILD
```

Start

```shell
▀ ╢█████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░╟
$ $CMD_START
```

## Docker Install

```
development : dockerfile.development
production  : dockerfile.production
test        : dockerfile.test
```

### Docker Development

```docker
docker-compose -f "docker-compose-development.yml" up -d --build
```

### Docker Production

```docker
docker-compose -f "docker-compose-production.yml" up -d --build
```

### Docker Test

```docker
docker-compose -f "docker-compose-test.yml" up -d --build
```

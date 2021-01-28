# Issues
Issues is an application that pulls down issues from specified GitHub repositories via passing command-line arguments. This application is based off a project in Dave Thomas' book, Programming Elixir 1.6.<br>
https://pragprog.com/titles/elixir16/programming-elixir-1-6/
<br>
## Dependencies
(1) Erlang OTP 23.2+<br>
https://www.erlang.org/downloads
<br>
## Installation
(1) Download `ex_github_issues_app` repository by running either of the following commands in your CLI: <br>
ssh: &nbsp; `git pull git@github.com:glitchy/ex_github_issues_app.git` <br>
https: `git pull https://github.com/glitchy/ex_github_issues_app.git`
<br>
## Run
(1) Move into top level directory.<br>
(2) Run `./issues {username} {repo} {count}`
<br>
### N.B.
If only two arguments are passed (`{username}`, `{repo}`) the default value for `{count}` is 4.<br>
Pass `-h` or `--help` as first argument for help documenation.

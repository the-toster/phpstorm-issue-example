# Issue
Unable to delete invalid content root - it restores every time project open.

# Steps to reproduce
- clone & install dependencies
```
git clone git@github.com:the-toster/phpstorm-issue-example.git`
cd phpstorm-issue-example
composer install
```
- open `phpstorm-issue-example` in `PHPStorm`
- delete `tests/Unit` from `Settings` - `Directories` - `Content root`
- Click `Ok`
- reopen project

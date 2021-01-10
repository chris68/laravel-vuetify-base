All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## ## 2021-01-10

### Added

- Upgrade Vue to Vue 3.03 (was not 3.03 yet...)
- Enable Vue with the one example component (=> show it in home)
- Adapt gitignore 
- Added SourceMaps

## 2021-01-09

### Added

- Install snap node      12.19.0    3292   12/stable      iojs✓             classic
- Initial create with laravel 8 (`composer create-project laravel/larvel <Project>`)
- Added Vue 3 as standard
  `npm i -D laravel-mix@next vue@next @vue/compiler-sfc vue-loader@next`
- Added Laravel ui  
  `composer require laravel/ui`
- Scaffolding UI  
  `php artisan ui vue --auth`  
  Marked the places for rework with @todo
- Postgres as database  
  Changed .env  files  
  `artisan migrate`  
  `artisan serve` now works with /register and /login links
- Mails to log instead to server
- Locale de  
  `composer require laravel-lang/lang:~8.0 --dev` (=> vendor\laravel-lang\lang)  
  Copy `de` files to `resources\lang`
- Debug Toolbar  (https://github.com/barryvdh/laravel-debugbar)  
  `composer require barryvdh/laravel-debugbar --dev`
  
## Template

### Added

### Changed

### Removed


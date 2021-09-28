# Changelog

All notable changes to `laravel-revisions` will be documented in this file

## 5.0.0 - 2020/10/06

- Support Laravel 7.x

## 4.0.0 - 2019/13/11

- Support Laravel 6.0

## 3.1.0 - 2019/15/05

- Delete future added child related records when rolling back

## 3.0.3 - 2019/16/04

- Allow for revisions to contain timestamps
 
## 3.0.2 - 2019/12/04

- Fixed relations with custom pivot accessors
- Fixed `saveAsRevision()` method expecting default model return type 

## 3.0.1 - 2019/22/03

- Added support for excluding certain fields when creating a revision.

## 3.0.0 - 2019/22/03

- Support Laravel >= 5.8
   - breaking change: `bigInteger` column type on `users` table -> affects foreign key constraints on `users` table

## 2.0.0 - 2019/22/03

- Transferred ownership to the [vildanbina](https://github.com/vildanbina) organisation
- Changed package name in `composer.json` file from `zbiller/laravel-revisions` to `vildanbina/laravel-revisions`
- Changed namespace from `Zbiller\Revisions` to `vildanbina\Revisions`
- Updated continuous integration badges to point to the newly transferred repository  

## 1.0.0 - 2019/2/15

- Initial release

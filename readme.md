# Automatic translator

This is a package that allows automatic translation of strings where there is not a valid explicit translation in the project.

## How to Use

1. Run `composer require powlam/automatic-translator`
2. Just use translations as usual: `__('This text must be translated')` 

If there is already an explicit translation defined into the project, this will be used.

Otherwise the package will translate it:
- Origin language: `config('app.locale')`
- Destination language: `App::currentLocale()`

---

## More from Powlam

- [Github](https://github.com/powlam)

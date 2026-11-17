# mySpace (2021) — early browser-development project

A small collection of client-side exercises built with HTML, CSS and JavaScript and served through a simple PHP entry point. It includes a clock, a browser to-do list, and a diary with local text file import/export.

## Scope and limitations

- The to-do list exists in the current browser page and is not persisted across page reloads.
- The diary reads/writes files through browser interactions; it has no account system or hosted backend storage.
- There is no authentication, automated CI test suite, production backend or managed deployment.
- `index.php` includes `home.html`. A local PHP server can be started with `php -S localhost:8000`; open http://localhost:8000.

This repository is preserved to show the development journey, not as evidence of a maintained modern production application.

**Portfolio recommendation:** archive through the GitHub repository settings once you have reviewed this README. Archiving is a separate settings operation and does not delete history.

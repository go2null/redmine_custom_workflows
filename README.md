redmine_custom_workflows
========================

mirror of http://redmine.academ.org

Git mirror of the Redmine Custom Workflows plugin, as I couldn't find one.
* Homepage: http://redmine.academ.org
* Redmine: http://www.redmine.org/plugins/custom-workflows

Changelog
---------

### 0.0.4 (2012-10-08)

_Compatible with Redmine 2.1.x, 2.0.x, 1.4.x, 1.3.x, 1.2.x._

* Added ability to enable workflows globally for all projects. No need to enable 'Custom workflows' project module anymore. Just go to the 'Administration' -> 'Custom workflows' section and enable or disable your workflows in one place.
* Fixed bug with 'Status transition prohibited' when updating the issue status by the repository commit

Don't forget to migrate plugins after installing the new version.

### 0.0.3 (2012-09-10)

_Compatible with Redmine 2.1.x, 2.0.x, 1.4.x, 1.3.x, 1.2.x._

* Added compatibility with 1.2.x, 1.3.x

### 0.0.2 (2012-09-08)

_Compatible with Redmine 2.1.x, 2.0.x, 1.4.x._

* Added ability to define after_save script along with before_save
* Changed context of the script executing to the issue itself.
* Improved logging

### 0.0.1 (2012-09-03)

_Compatible with Redmine 1.4.x, 2.0.x, 2.1.x._


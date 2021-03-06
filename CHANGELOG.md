# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

### Unreleased

##### Fixed

* Don't rely on :class_name option being set on association to identify its class.

### v1.0.0

##### Changed

* Update select 2 to version 4.
* Set DateTimePickerInput default options from gem's setup block.
* Rename :ajax_filter to :search_select_filter.
* Rename :range_select to :numeric_range_filter.

### v0.12.0

##### Added

* Add selected list input to handle many to many associations.

### v0.11.0

##### Added

* Add ability to enable select2 for specific select controls
* Make default select configurable.
* Add initializer to setup addons.
* Add automatic deployment on tags push through travis.
* Enable allowClear in select2_search.
* Allow :order option if Ajax Search.
* Respect date_time_picker input_html[:value].
* Allow date_time_picker in ActiveAdmin custom pages.
* Allow customizable select2 values.

##### Fixed

* Replace slashes to underscore in module name.

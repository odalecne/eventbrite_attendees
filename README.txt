Eventbrite Attendees
====================

A simple Drupal 7 module that adds a new block to the system for showing a list
of attendees to an Eventbrite event.

Usage
-----

* Install the module
* Visit `/admin/structure/block/manage/eventbrite_attendees/eventbrite_attendees/configure`
  and provide your Eventbrite OAuth token and Event ID
* Visit `/admin/structure/block` and add the Eventbrite Attendees block

Features
--------

* Profile fields selection through UI
* Fully customizable attendee list via theme/template system
* Cache JSON response list of attendees
* Token replacement for contextual node when placed on a node route

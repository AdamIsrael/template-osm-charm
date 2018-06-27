# Reactive Charm Template for OSM charms using Python

This is a template for creating an OSM charm using the reactive charm pattern, with handlers written in Python.
It is intended for use with [charm-tools][] and the `charm create` function.

## Notes

This template is a current work in progress to support a refactored class of layers to create "OSM" charms, which may or may not be a proxy charm, but all of which follow a pattern where operations are driven through `actions`.

## Usage

This is an optional template when creating a new charm with `charm create`.
First, make sure you have [charm-tools][] installed:

```
sudo apt-get install charm-tools
```

Then just run the create command:

```
charm create my-charm -t template-osm-charm
```

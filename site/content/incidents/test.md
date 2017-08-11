+++
# default attributes for an incident.
#
title = "Test"
date = 2017-08-11T16:06:20+02:00

# severity: represents the impact of 
# your system due to the current incident.
# This is the list of supported severities:
#
# - under-maintenance
# - degraded-performance
# - partial-outage
# - major-outage
#
severity = "degraded-performance"

# affectedsystems: is a list of systems affected
# by the incident.
# Example:
# affectedsystems = ["API", "Build servers"]
#
affectedsystems = ["Discord"]

# resolved: marks an incident as resolved.
# It can be either true or false.
#
resolved = false
+++

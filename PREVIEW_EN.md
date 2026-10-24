# Fictional example: CHG-001

Change: add lab VLAN 120 on LAB-SW01.
Window: November 1, 2026, 20:00–20:30, America/Toronto timezone.
Objective: connect two isolated test workstations.
Prerequisites: identified backup, verified console, approved VLAN and ports.
Steps: capture baseline; create VLAN using the validated procedure; assign the two approved ports; test.
Success: both clients reach the lab gateway; access to management VLANs is blocked.
Rollback: lost management access or unsuccessful tests at 20:15; restore the validated previous configuration.
Evidence: before and after outputs, allowed and forbidden traffic tests, final approval.

All device names are fictional. Replace this example with approved steps appropriate to the environment before implementation.

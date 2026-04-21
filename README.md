# Nginx Security Dashboard

A lightweight Flask-based dashboard for visualizing Nginx security log analysis, suspicious traffic patterns, request anomalies, and candidate IP blocklists.

## Overview

This project provides a simple web dashboard for structured Nginx security analysis data.

It is designed to visualize JSON reports generated from access log analysis and make suspicious traffic easier to review in a browser.

The dashboard highlights:

- top source IPs
- most requested paths
- suspicious paths
- suspicious keywords
- request anomalies
- candidate IP blocklists

## Features

- loads structured Nginx security analysis data from JSON
- displays top source IPs and request categories
- shows frequently requested paths and suspicious paths separately
- visualizes suspicious keyword hits
- summarizes malformed, empty, and non-HTTP requests
- displays candidate blocklist IPs for manual review
- provides a simple browser-based view for security-oriented log analysis

## Requirements

- Python 3.10+  
- tested with Python 3.13

## Project structure

```text
nginx-security-dashboard/
├─ README.md
├─ requirements.txt
├─ .gitignore
├─ app.py
├─ data/
│  ├─ .gitkeep
│  └─ nginx_report.json
├─ templates/
│  └─ index.html
├─ static/
│  └─ style.css
└─ docs/
   └─ ideas.md

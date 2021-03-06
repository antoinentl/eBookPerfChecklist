# eBookPerfChecklist
A progressive web app to help you boost eBook performance

## How-to

### Use

**If you’re using a mouse/touch:**

- click the checkbox to check
- click the label to display details
- click the “Thanks button” if you don’t need SVG, JS or animations
- click reset to… reset the checklist

**If you’re using a keyboard:**

- press “tab” to navigate items
- press “enter” to check
- press “space” to display details
- press “backspace” to reset the checklist

Don’t worry, your checklist is autosaved: you can close this website, your current checklist will be retrieved when reopened.

### Install

If you’re on iOS/Android/Windows 8–10, you can actually install this web app. Just visit the page and “Add to homescreen”.

Thanks to service workers, it will even work offline on Android, Chrome, Opera or Firefox (connection required on iOS).

## Summary

The eBook Performance Checklist is part of the Blitz Project. It’s a progressive web app which aims is to help you boost your eBooks’ performance.

It is currently in v.0.41 (Marble Marshmallow) and available [on this page](https://friendsofepub.github.io/eBookPerfChecklist/).

## Details

This web app is just a glorified form with checkboxes.

- We’re using JS to toggle details.
- We’re using `localStorage` (with cookie fallback) to store checked checkboxes + progress (bar’s width).
- We’re using Service Workers to make it work offline—when supported.
- Keyboard features are implemented via JS when needed.

And that’s it. 

## License 

eBookPerf checklist, a Blitz optimization tool to help you achieve great performance in eBooks

Copyright (C) 2016–present Jiminy Panoz

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with this program.  If not, see [http://www.gnu.org/licenses/](http://www.gnu.org/licenses/).

### What LGPL3 actually implies

You can fork this repo and make your own checklist/web app, say for Quality Assurance, InDesign’s export cleaning, metadata, etc. You can use it in commercial projets but your modifications to this specific part (consider this a library) should then be released with a LGPL3 license. Attribution is needed in any case.

### Why LGPL3 OMG it’s not MIT like the Blitz Framework!

The eBook dev ecosystem is a nightmare, we need eBook tools. And fast!

Very few people actually release those tools. Now it’s just a checklist so why would you want to keep this closed source, huh?

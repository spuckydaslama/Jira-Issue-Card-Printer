# Jira-Issue-Card-Printer
Jira Issue Card Printer by https://github.com/qoomon

### Fork
I removed the GA Tracking

### Card Layout
![Card Layout](CardExample.png)

### Installation
#### Drag'n'Drop
got to [Instalation Site](https://spuckydaslama.github.io/Jira-Issue-Card-Printer/bookmarkInstalation.html)

*or*

#### Manually
Create Bookmark with folowing content.
```
javascript:(function(){ var script = document.createElement("script"); script.src = "https://spuckydaslama.github.io/Jira-Issue-Card-Printer/bookmarklet.js"; document.body.appendChild(script); document.body.removeChild(script);})();
```

### Usage
Just select Issue(s) then run the Bookmarklet.

Marker to separate description into print and no print area ("~~~~~")

#### Select multible issues
##### Jira Agile
holding STRG / CMD or SHIFT and click on issues
##### Jira Classic
search for issues und select *List View*

### Support
#### Browser
* **Chrome Browsers 46+**
* **Safari 9+**.

#### Issue tracker
* **Jira**
* **Trello**
* **PivotTracker**
* **YouTrack**

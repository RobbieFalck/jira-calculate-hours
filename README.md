# jira-calculate-hours
Modified jQuery tampermonkey script to total up Jira columns

Modified script of https://github.com/toomasr/jira-calculate-hours

Added capability to sum up custom numberic fields on Jira filters and Jira Dashboards

# Motivation
I wanted to get total SUM values of custom fields on jira dashboards to avoid buying a plugin.

To achieve that I modified a JavaScript snippet from https://github.com/toomasr/jira-calculate-hours that you can paste into Tampermonkey or equivalent.

# Quick Start
Grab the script from jira-calculate-hours-dashboard.js

# You Need More Help?
* Install Tampermonkey
* Open up Tampermonkey and create a new script
* Copy paste the script from jira-calculate-hours-dashboard.js.
* Modify @include URL in the header to match your JIRA url
* Navigate to your JIRA dashboard and see the results

# Screenshot
![image](https://user-images.githubusercontent.com/32743781/166893497-f8a8aef4-c27f-40c3-93b1-25a540303a57.png)

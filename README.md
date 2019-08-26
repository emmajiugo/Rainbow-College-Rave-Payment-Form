# Rave Payment Forms for Schools
How to use:
- Download the plugin from here
- Install the plugin on your Wordpress plugin section
- Go to `Student Record` section of the plugin, download the CSV format sheet, Populate ypir students' records and upload back.
- Go to `API Keys Settings` and enter your Public and Secret keys from your Rave dashboard.

Setting Fees Form:
- Go to `Add New` and enter the below in the box
```
[text name="Student ID" required="required"]
[text name="Student Name" required="readonly"]
[text name="Student Class" required="readonly"]
```
- Add form title (eg: School Fees)
- Click the `Publish` button
- Copy the shortcode generated (eg: `[rave-form id="25"]`) and paste in your page
- The shortcode should load the form on the page

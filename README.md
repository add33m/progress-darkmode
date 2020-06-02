# Progress Dark Mode
 A dark mode for ThorenGruppen's Progress via the Stylus plugin for Firefox/Chrome/Opera

## How do use

1. Download the Stylus plugin for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/), [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne/) or [Opera](https://addons.opera.com/en/extensions/details/stylus/). You can find the official website and source code for the plugin [here](https://add0n.com/stylus.html) if you don't trust it. (**DO NOT** USE THE "STYL*ISH*" PLUGIN, AS IT HAS MAJOR PRIVACY FLAWS)
2. [Go to the page for this userstyle](https://userstyles.org/styles/175794/progress-dark-mode) and hit "Install Style". If you want to modify how your dark mode looks, refresh the page and click customize settings to open up the color pickers. When you are done, simply hit "Update Style". The styles will automagically be loaded into Progress without the need to refresh!
3. Optional - if you know a bit of CSS and want to modify the style to fit you more than is possible with the color pickers, click the stylus plugin icon in your browser and click the little pen icon next to "Progress Dark Mode" (you need to be on Progress to have this option). This will allow you to directly edit the CSS that is injected into Progress by the plugin. Please note that if you make changes and then update or reinstall the style from userstyles.org, your changes will be overwritten and removed!
4. Enjoy not staring into the sun whenever you use Progress! :D

If you want to temporarily turn off Dark Mode, go to Progress, open the stylus plugin modal and tick the little box next to Progress Dark Mode.

## Description (from userstyles.org)

A custom made dark mode for Progress (a school site for schools owned by Thorengruppen AB). This will probably not work anywhere else!

To edit colors, hit Customize Settings. I DO NOT recommend changing anything but the schedule and possibly unread message colors, or it might look very weird. If you accidentally changed them, the defaults are: Light - #525252, Medium - #414141, Light - #313131.

Feel free to use this as much as you like. If you want to make a new theme based on this one, feel free to do so as long as you give me some credit :)

It is also customized for TIS schools since the original logo has black text and isn't transparent. To change to your school's logo, just edit the URL in the .logo CSS class.

## Update log

27/11 2019:
- Fixed a bug where the tooltip on the IUP page had a white background

25/11 2019:
- Made the div that makes the schedule events appear lighter than whole-day events fully invisible

18/11 2019:
- Fixed a minor bug with alerts

11/11 2019:
- Added support for home page alerts

5/11 2019:
- Added a proper yellow list object color
- Switched the colors for lists containing green, red, blue and yellow list entries, to now be dark by default and lighter when hovered on

24/10 2019:
- Fixed some things/hotted up the message sending box
- Restructured colors to allow more options

1/10 2019:
- Added option for schedule color
- Removed profile pic overwrite
- Added padding to schedule objects
- Removed links to appstore/playstore
- Other bugfixes

## About
I made this because I didn't like the default look of Progress. However, I am merely a student at the school and have no association with Thorengruppen.
While using this style provides you with no security risks, it may contain bugs, and I am in no way responsible for how you use this.
FYI - this repo was made long after the original userstyle was published. That's why a lot of updates are missing in the commit history!

[Click here to go to the official Userstyle I made at userstyles.org!](https://userstyles.org/styles/175794/progress-dark-mode)

## Contributing
Please do contribute to this style if you can! I am a student at TIS in Helsingborg and will be for the period summer 2018 to summer 2021. After that period I will no longer be able to keep this repo active as I will no longer have access to the site. I have done my best to make this work as well as possible but will probably not work properly for teachers and may be broken for other schools (TBS/Yrkesgymnasiet).

The code in this repo is designed to work with [userstyles.org](https://userstyles.org/). Please keep [their syntax](https://userstyles.org/help/coding#help-style-settings) when writing pull requests (basically just don't change the weird commented out stuff in :root that looks like this: `/*[[something]]*/`)!
If I don't respond to pull requests, please upload your own style on userstyles.org. Just remember to give some credit :)

## Honorary mentions
Thanks from pelp3 for the original idea and some help with the original CSS.

Also check out the "Progress Ugly Mode" version that my friend [the0val](https://github.com/the0val) made [here](https://userstyles.org/styles/176575/progress-ugly-mode)!

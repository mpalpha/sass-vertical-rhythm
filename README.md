##sass-vertical-rhythm

Name: SASS vertical rhythm technique  
Description: sass-vertical-rhythm is a technique used to create vertical ryhthm based on a base unit value.  
Copyright (C) 2015  Jason Paul Lusk (Jason@jasonlusk.com)  
Author: Jason Lusk  
Author URI: http://JasonLusk.com  
GIT URI: https://github.com/mpalpha/sass-vertical-rhythm.git  

####DEMO <a href="http://codepen.io/mpalpha/pen/QbeMMN" target="_blank">http://codepen.io/mpalpha/pen/QbeMMN</a>

#####Requirements:
  SASS v3.2+ tested with libsass

#####Use:
```sass
    @include vr(16, 40, false);
```

#####Configure:
Available Options|Default value|Description
-------------|-------------|-------------
$fontSize|n/a|font size
$from|n/a|parent font size
$baseline|true|toggle vertical alignment to the baseline

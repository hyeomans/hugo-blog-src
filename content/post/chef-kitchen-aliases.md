+++
date = "2017-08-13T00:00:00Z"
keywords = ["Chef"]
tags = ["journal"]
title = "Chef Kitchen Aliases"
slug = "chef-kitchen-aliases"
+++

Kitchen converge usually takes a lot of time to complete. Sometimes I leave it running and forget about it,
so I created aliases that notify me when kitchen has finished.

<!--more-->

```
alias kc="kitchen converge; osascript -e 'display notification \"Kitchen converge finished\" with title \"Kitchen Converge finished\"'"
alias kd="kitchen destroy; osascript -e 'display notification \"Kitchen destroy finished\" with title \"Kitchen Destroy finished\"'"
alias kv="kitchen verify; osascript -e 'display notification \"Kitchen Verify finished\" with title \"Kitchen Verify finished\"'"
alias kt="kitchen test; osascript -e 'display notification \"Kitchen Test finished\" with title \"Kitchen Test finished\"'"
```

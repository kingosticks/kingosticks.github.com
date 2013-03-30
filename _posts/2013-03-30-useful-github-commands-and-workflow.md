---
layout: post
category : lessons
tagline: "Useful stuff I keep forgetting"
tags : [github, mopidy, python, commands]
---
{% include JB/setup %}

* Checkout the remote branch ```feature/some-thing``` from my repo:

    ```git checkout --track origin/feature/some-thing```

* Add the upstream (```mopidy/mopidy```) repo so we can pull from / push to it:

    ```git remote add upstream git://github.com/mopidy/mopidy.git```

* Update my local repo to most recent upstream (```mopidy/mopidy```) version:
   
    ```git pull upstream develop```

* Push changes in my local repo to my forked repo (```kingosticks/mopidy```):

   ```git push origin develop```

* Push a new local branch to my remote repo:
    
    ```git push -u origin feature/my-new-branch```

* Delete all old files and directories in my local repo:
    
    ```git clean -f -d -x -m```

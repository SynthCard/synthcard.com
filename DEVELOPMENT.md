# Developer Guide

## Contribute
I used [Hugo](https://gohugo.io/) do develop this site.


## Deploy
Deployment of changes is done by pushing new markdown into the `main` repo. A Github Action would trigger deployment automatically to [synthcard.com](https://synthcard.com).


You won't have to do this unless we're switching deployment targets.

Setup deploy keys:
- Create a deploy key with write access on target repo: https://github.com/SynthCard/synthcard.github.io/settings/keys
- Add action secret on source repo: https://github.com/benjiaomodular/benjiaomodular.com/settings/secrets/actions
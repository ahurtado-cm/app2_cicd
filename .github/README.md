github actions configuration
------------------------------
- create secret 
in github goto profile / settings / developer settings / personal accss tokens
  create new personal access token (classic)
  name it PAT_TOKEN_2
  assing scope  repo (full control)
in github, go to project settings
  general / security / secrets and variables / actions
  create new repository secret
  call it PERSONAL_2
  the value would be the one genrated with PAT_TOLEN_2

or in project settings
  general / code and automation / actions/ general
  set wojkflow permissions to read and write (to work with GITHUB_TOKEN)
  
crete secrets required by the project.

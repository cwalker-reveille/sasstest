# sasstest
test for sass issue

Test Case:

npm run sass-dev:administration

Update and do a save on SASS/_test2.scss
  Note that the CSS recompiles
  
Update and do a save on SASS/Administration/_collectors.scss
  Note that it will not recompile the CSS
  
reinstall any sass before 1.32.0 and repeat the previous steps.
In my case saving either SASS/_test2.scss and SASS/Administration/_collectors.scss  will cause a recompile

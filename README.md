## git can be configure in total 3 ways

1. is system wide wise using the --system flag for this you need the admin preveledge to make those configuration
   like for exaple git config --system use.email (what ever is your email address is).

## git can be cofigure global wise using the --global flag

1. this config mainly is for the current user and it will be used for all the repositories that you will be working on.
   like for example git config --global user.name (what ever is the user name);

## git also can be configure with local for specific folder wise

1. this configuration does not need any flag to be configure and it will be used only for the specific folder that you are working on.
   for example git config user.email (what ever is the email address is).
   --- but the priority and precidence will be different for each
   localconfig > globalconfig > systemconfig (high to low)

---

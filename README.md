# unichirsite

- need to make the changes he sent me
About:
- about us page was never finished, it still has lorem ipsum on it, not linked to anywhere on the site, what does he want to finish it?
- using sendinblue for emails -> they work

List of unlisted pages:
- 4 element yoga
- about us
- need to add him as admin in analytics once it goes through


- ask if he has any other patient reviews that he wants put up
- check the automatic updates

can only get into the site through siteground, sigure out why -> deactivated siteground security plugin, now the login works, why? try to figure it out
- find a new seurity plugin, or see if the security plugin works now w/o causing issues for login -> is still a problem, figure out another security plugin

css to remove side bar from mobile menu
@media screen and (max-width: 920px)
{
	.sidebar-main {display:none;}
}



- the security plugin still locks users out, keep it off
- figure out why php upgrades crash the site

try removing every inactive plgin to fix the php issue, can only work on it in the morning on sat / sun
also try turning off the active plugins, could the plugin that lets people make appointments be causing the issue?


- need to figure out why the php won't update, its becoming an issue
- could be caused by the appointment plugin? try again on saturday

// removed from the widget, keeping it here incase he wants it back

   <label style="background: url(/wp-content/themes/medica-parent/images/icons/icon_mail_small.png) 0 2px no-repeat; padding-left: 22px; margin-right: 3px; font-style: italic;">You can email us</label>

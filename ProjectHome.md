# Introduction #
This repository contains a large selection of British cable (Virgin Media), satellite (Freesat and Sky) and terrestrial (Freeview) television channel and radio station logos for use with [MediaPortal](http://www.team-mediaportal.com/) and the [LogoManager plugin](http://www.team-mediaportal.com/extensions/utilities/logomanager).

If the logo you require isn't in this pack, let me know or create your own. Please check that the channel you require is not due to close in the near future before requesting, you can use [this terrestrial list](https://en.wikipedia.org/wiki/List_of_digital_terrestrial_television_channels_%28UK%29#Future_channels_and_events), [this Sky list](http://www.tvchannellists.com/List_of_Channels_on_Sky#Future_EPG_changes_TV) or [this list](http://www.tvchannellists.com/Forthcoming_changes_to_digital_platforms_%28UK_%26_Ireland%29) for information. If you do make your own logos for a channel, please consider sharing them with the rest of the community by posting them in [this thread](http://forum.team-mediaportal.com/threads/uk-tv-radio-logos.87737/).

Thanks to cheetah05, jsimo01, Mew, TritonT, wonkyd and others for their work on the previous [UK TV & Radio Channel Logos plugin](http://www.team-mediaportal.com/extensions/tv-channels/uk-tv-radio-channel-logos) and [TV, Radio, Website, Weather & Automation Logos (mainly UK) packs](http://forum.team-mediaportal.com/threads/tv-radio-website-weather-automation-logos-mainly-uk.26137/), as well as Edalex and Vasilich for the development of LogoManager and their assistance.

# Instructions #
## Mediaportal 1 ##
Download and install the LogoManager plugin through MediaPortal Extension Installer or via [the MediaPortal website](http://www.team-mediaportal.com/extensions/utilities/logomanager). Argus TV Recorder users must install and use Logomanager on the same machine as their server.

Open MediaPortal (not MediaPortal Configuration), on a first run LogoManager will attempt a grab in 30 seconds if you're in a supported country and the 'All Channels' group has less than 200 channels or all groups except 'All Channels' have less than 200 channels.

For more options select LogoManager from the Plugins section of MediaPortal (not MediaPortal Configuration).

Under **Package** select the country you wish to use, e.g. _'British Pack'_, if it hasn't automatically been selected.

Under **Channel Group** choose the group(s) you wish to scan for, e.g. _'All Channels'_, then click 'Ok'. Note that TV and Radio are in separate groups. At this point you can select another package, when asked to save your selection choose 'Yes' and multiple packages can be grabbed in one go, choose 'No' and only the last selected package will be chosen.

Under **Design** you may choose from a variety of background effects, with _'Simple'_ being plain, examples are displayed and you can change this later.

Finally select **Grab Now** and wait for the dialogue confirming the number of logos that have been grabbed. In some skins a progress bar is displayed during the process, with the top bar representing the progress though the channel group, and the bottom bar representing the total progress.

You may now change packages, scan additional groups, change designs or exit the plugin. In the latter case, you will be asked if you wish to rebuild your cache, select 'Yes' if you have grabbed any logos but make sure that you have stopped playing any media as this will cause MediaPortal to crash. The settings will be retained for the next time you use LogoManager and a grab will automatically be conducted every 7 days after the the previous grab (this can be modified by editing 'AutoGrabIntervalInDays' in LogoManager.config), using those settings, if there are less than 200 channels.

### Optional ###
The logos in this repository are designed to be used with Simple against darker backgrounds, as most MediaPortal skins are in areas such as the TV Guide and Mini Guide, including parts of [Avallanche](http://www.team-mediaportal.com/media/com_mtree/images/listings/o/2043.png). However most [WebMediaPortal](http://www.team-mediaportal.com/media/com_mtree/images/listings/o/1838.png) skins and some mobile apps such as [aMPdroid](http://forum.team-mediaportal.com/attachments/mobile-3-png.115337/) use lighter backgrounds.

To get around this you can either use a dark design, such as Dark Glass, or add a black glow around the logo. The latter can can be done by placing [this Design.settings file](https://mediaportal-uk-logos.googlecode.com/svn/trunk/Design.settings) (right-click and choose Save Link As...) into the `\ProgramData\Team MediaPortal\MediaPortal\Thumbs\LogoManager\designs\[Name of Design used]` folder and running another grab. I have only testing that Design.settings file against the Simple design, it may need adapting for others.

## Mediaportal 2 ##
LogoManager is included with MediaPortal 2 as of the [10th Anniversary Edition Update 1](http://www.team-mediaportal.com/news/mp2-10th-anniversary-update-1). Logos will be maintained at a central repository, located at http://channellogos.nocrosshair.de/ListChannels.aspx. Currently, this is mainly set-up for test purposes and isn't maintained or regularly updated.
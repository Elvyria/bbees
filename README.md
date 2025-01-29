# runit-candies
Collection of useful service files for runit service manager.

## System
- 🍬 *[zram](./system/zram)* — super simple service that will help you with the advanced zram configuration.  

    📦   Util-Linux

## User
- 🍬 *[snooze-*](./user/snooze)* — snooze is a simple alternative to cron and these services will allow you to run user scheduled tasks and configure the schedule through simple [conf](./user/snooze-daily/conf) files.  

    📦   Snooze, Run-Parts

## Desktop
- 🍬 *[librewolf-sync](./desktop/librewolf-sync/)* — service that keeps your browser profile in RAM and occasionally makes an atomic sync back to the cold storage. Default [configuration](./desktop/librewolf-sync/conf) won't make sense for your setup and is not optional.  
Make sure to backup your profile if you want to proceed.  

    📦 Rsync with [Atomic-Rsync](https://raw.githubusercontent.com/RsyncProject/rsync/refs/heads/master/support/atomic-rsync), BindFS


- 🍬 *[librewolf-nvidia-vaapi](./desktop/librewolf-nvidia-vaapi)* — service for the Flatpak versions of Firefox/Librewolf/... that sets up required variables and provides access to libraries for [nvidia-vaapi-driver](https://github.com/elFarto/nvidia-vaapi-driver).  

    📦   Flatpak, BindFS (Recommended)

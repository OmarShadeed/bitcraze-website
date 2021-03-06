---
layout: page-left-menu
title: Troubleshooting
permalink: /troubleshooting/
page_id: support-troubleshooting
---

{% si_intro Crazyflie 2.X Python cfclient connects but does not communicate %}
{% endsi_intro %}

{% si_step Update to latest cfclient %}
Follow this guide to update to the [latest cfclient.](/getting-started-with-the-crazyflie-2-0/#update-src)
Then proceed with [updating](/getting-started-with-the-crazyflie-2-0/#update-fw) the firmware.
{% endsi_step %}

{% si_step Update to latest firmware %}
Follow this guide to download the [latest firmware.](/getting-started-with-the-crazyflie-2-0/#latest-fw)
Then proceed with [updating](/getting-started-with-the-crazyflie-2-0/#update-fw) the firmware.
{% endsi_step %}

{% si_intro Crazyflie 2.X Android client does not connect %}
{% endsi_intro %}

{% si_step Check compatibility %}
Check that your Android device supports Bluetooth smart/low energy and your Android version is equal or greater than 4.4. Also check the [compatibility list](https://wiki.bitcraze.io/doc:crazyflie:client:cfandroid:index#android_device_compatibility) in the wiki.
{% endsi_step %}

{% si_step Do not pair%}
Do not pair your Android device to the Crazyflie 2.X like other Bluetooth devices. Just connect directly through the app. If you have paired it already, unpair it and try again.
{% endsi_step %}

{% si_intro Crazyflie 2.X does not take off %}
{% endsi_intro %}

{% si_step Make sure propellers are mounted correctly %}
Check that the propellers are mounted on the correct motor. Check each propeller 
to see if it is a clock wise or a counter clock wise turning propeller and mount it according to the detailed view below.
{% img Crazyflie 2.X propeller mounting; medium; /images/getting-started/cf2_props.png %}
{% endsi_step %}

{% si_step Make sure propellers are mounted with right side up %}
Check that you can see a little "ring" on every propeller's center otherwise the propellers are mounted upside down.
{% endsi_step %}

{% si_intro Crazyflie 2.X flies badly %}
{% endsi_intro %}

{% si_step Check center of gravity %}
Check that the Crazyflie 2.X is well balanced and adjust the battery and connector until it is. Holding the Crazyflie 2.X in the small "ears" is a easy way to test it.
{% endsi_step %}

{% si_step Balance propellers %}
Vibration is a normal cause for decreased flight performance. Try balancing the propellers using [this](/balancing-propellers) guide
{% endsi_step %}

{% si_step Check that all propellers turn freely%}
Check for hair stuck in any of the propellers/motors. It can also be that one of the motors are worn out or damaged. This is a bit harder to check. It is most likely the motor towards the direction the Crazyflie 2.X takes off. Try to listen for strange sounds when blowing on the propeller attached to it.
{% endsi_step %}

{% si_step Check for bent motor axis %}
Check each motor axis if it is bent as it causes vibration. This can be done by either applying a bit of thrust from a client or by blowing on the propeller and looking at the axis from above. If it is bent it might be possible to straighten it with a pair of pliers. If that doesn't work the motor needs to be replaced.
{% endsi_step %}


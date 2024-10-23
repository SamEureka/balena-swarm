# balena-swarm
A balena.io powered docker swarm auto-magical with Charlie Unicorn sparkle.


## Swarm Setup (manager & workers)

### Step One (Assumes you have an [account](https://docs.balena.io/learn/accounts/account/#sign-up))
* Get you an api key from [balenaCloud - Preferences](https://dashboard.balena-cloud.com/preferences/access-tokens) 

> [!IMPORTANT] [API Key - Documentation](https://docs.balena.io/learn/accounts/account/#api-keys)

* Create a fleet [Here](https://dashboard.balena-cloud.com/fleets). You will want to match your hardware/device type to the options available in the `Default device type` dropdown select menu. 
> [!NOTE] Keep in mind that currently you can only have one architecture type in a fleet. e.g. You cannot mix x86_64 and AARCH64 devices in the same fleet.  

> [!IMPORTANT] [Create a Fleet - Documentation](https://docs.balena.io/learn/getting-started/genericx86-64-ext/python/#create-a-fleet)

* Add a device to your created fleet and download the balenaOS image to install on the device.

> [!IMPORTANT] [Add a device - Documentation](https://docs.balena.io/learn/getting-started/genericx86-64-ext/python/#add-a-device-and-download-os)

### Step Two - Manager Node Instructions

> [!CAUTION]
> Write concise understandable instructions and leave them here.

### Step Three - Worker Node Instructions

> [!CAUTION]
> Write concise understandable instructions and leave them here.

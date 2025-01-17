# bot-miner-setup

setup instructions for side-by-side GPU mining and transcoding w/ LivePeer

As time goes on, alternative installation options will be added, but for now, this document is based on Ubuntu 18.04 LTS.

Go through the following installation steps, in order:

* [cuda ffmpeg setup](ubuntu/cuda-ffmpeg-setup.md)

* [cuda livepeer setup](ubuntu/cuda-livepeer-setup.md)

* [ethminer systemd setup](ubuntu/ethminer-systemd-setup.md)

After following the [ethminer systemd setup](ubuntu/ethminer-systemd-setup.md) instructions, your GPUs will be mining Ethereum as a systemd service.

We can run the transcoding service in one of two ways:

* [testnet using the devtool](testnet.md)

or

* [offline mode](offline.md)
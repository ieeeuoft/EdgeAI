Welcome to IEEE's EdgeAI 2025 workshop. Let's get building!

At the Rate Symbol: @

The following lines of code are used for setup:

sudo apt update
curl -sL https://deb.nodesource.com/setup_20.x | sudo bash -
sudo apt install -y gcc g++ make build-essential nodejs sox gstreamer1.0-tools gstreamer1.0-plugins-good gstreamer1.0-plugins-base gstreamer1.0-plugins-base-apps
sudo npm install edge-impulse-linux -g --unsafe-perm
sudo apt install -y gstreamer1.0-libcamera

EdgeImpulse Login:
NODE_OPTIONS="--dns-result-order=ipv4first" edge-impulse-linux --disable-login

EdgeImpulse Runner:

NODE_OPTIONS="--dns-result-order=ipv4first" edge-impulse-linux-runner --disable-login

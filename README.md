# pve-no-subscription

## Git
Melde dich via ssh auf den Server an und stelle sicher das `git` installiert ist.
```bash
apt update
apt -y install git
```

## Download und ausführen
Repo Clonen und ausführen.
```bash
git clone https://github.com/PhilippKuhlmann/pve-no-subscription.git pve-no-subscription
cd pve-no-subscription
chmod +x pve-remove-subscription.sh
./pve-remove-subscription.sh
```
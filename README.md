# Build changes

apt-get install libncurses5 libtinfo5 bc bison build-essential ccache curl flex g++-multilib gcc-multilib git gnupg gperf imagemagick lib32ncurses5-dev lib32readline-dev lib32z1-dev liblz4-tool libncurses5-dev libsdl1.2-dev libssl-dev libwxgtk3.0-dev libxml2 libxml2-utils lzop pngcrush rsync schedtool squashfs-tools xsltproc zip zlib1g-dev repo adb fastboot

# Steps

mkdir lineage
cd lineage
repo init -u https://github.com/LineageOS/android.git -b lineage-16.0
repo sync
source build/envsetup.sh
breakfast vegetalte
croot
brunch vegetalte

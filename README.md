# Lineage buildscripts
========================

Starting from zero:
---------
    mkdir -p ~/android/lineage
    cd ~/android/lineage
    repo init -u git://github.com/LineageOS/android.git -b lineage-15.1
    curl https://raw.githubusercontent.com/lineage-o-x2/local_manifests/working/lineage-15.1/local_manifest.xml > ~/android/lineage/.repo/local_manifests/my_manifest.xml
    repo sync

If you've already synced Lineage-Sources:
----------
    curl https://raw.githubusercontent.com/lineage-o-x2/local_manifests/working/lineage-15.1/local_manifest.xml > /path/to/lineage/.repo/local_manifests/my_manifest.xml
    repo sync

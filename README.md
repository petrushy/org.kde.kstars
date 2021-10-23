# org.kde.kstars

This is some WIP (stalled?) to create a flatpak for kstars.

Build with

flatpak-builder build-dir org.kde.kstars.yaml

flatpak-builder --user --install --force-clean build-dir org.kde.kstars.yaml

flatpak run org.kde.kstars

flatpak run --command=sh --devel org.kde.kstars
FROM frankfang128/oh-my-docker:mangosteen

RUN yes | pacman -Sy archlinux-keyring; pacman-key --init; pacman-key --populate
RUN yes | pacman -Syu
RUN yes | pacman -S libyaml
RUN rvm install 3.3.4

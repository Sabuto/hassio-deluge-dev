ARG BUILD_FROM
FROM $BUILD_FROM

ENV PYTHON_EGG_CACHE="/config/plugins/.python-eggs"

RUN \
  echo "*** add repos ***" \
  apt-get update && \
  mkdir /etc && \
  ll -a /etc
  # apt-get install -y \
          # gnupg
  # apt-key adv --keyserver keyserver.ubuntu.com --recv-keys C5E6A5ED249AD24C && \
  # echo "deb http://ppa.launchpad.net/deluge-team/stable/ubuntu bionic main" >> \
	# /etc/apt/sources.list.d/deluge.list
  # echo "deb-src http://ppa.launchpad.net/deluge-team/stable/ubuntu bionic main" >> \
	# /etc/apt/sources.list.d/deluge.list && \
  # apt-get update && \
  # apt-get install -y \
  #         deluged \
	#       deluge-console \
	#       deluge-web \
	#       p7zip-full \
	#       unrar \
	#       unzip && \
  # echo "**** cleanup ****" && \
  # rm -rf \
	#      /tmp/* \
	#      /var/lib/apt/lists/* \
	#      /var/tmp/*
Bootstrap: docker
From: glotzerlab/software:latest

%labels
	MAINTAINER csadorf

%post
	ln -s /usr/bin/python3 /usr/bin/python
	apt-get update && apt-get install -y \
		python3-scipy \
		python3-matplotlib

%environment
	export LC_ALL=C

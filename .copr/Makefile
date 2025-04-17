srpm:
	dnf install -y fedpkg rpmdevtools
	rpmdev-spectool -g 389-ds-base.spec
	fedpkg --release epel9 srpm

	if [[ "${outdir}" != "" ]]; then \
	        mv *.src.rpm ${outdir}; \
	fi


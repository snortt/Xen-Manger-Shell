all: xen_manager_shell

xen_manager_shell: xen-manager-shell
	sudo dpkg-deb --build xen-manager-shell

clean: 
	@-rm -vf *.deb

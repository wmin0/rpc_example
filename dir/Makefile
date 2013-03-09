all:
	rpcgen dir.x
	cc rls.c dir_clnt.c dir_xdr.c -o rls
	cc dir_svc.c dir_proc.c dir_xdr.c -o dir_svc
clean:
	rm rls dir_svc dir_svc.c dir_clnt.c dir_xdr.c

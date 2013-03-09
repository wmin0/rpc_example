all:
	rpcgen msg.x
	cc rprintmsg.c msg_clnt.c -o rprintmsg
	cc msg_proc.c msg_svc.c -o msg_server
clean:
	rm rprintmsg msg_server msg_clnt.c msg_svc.c msg.h

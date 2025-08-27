hmf-centos-8:
	docker buildx build -t hub.hmf.xyz/base/hmf-centos:8 --platform linux/amd64 .
	docker push hub.hmf.xyz/base/hmf-centos:8

dolphinscheduler-baseos:
	docker buildx build -t hub.hmf.xyz/base/dolphinscheduler-baseos:8 -f Dockerfile-dolphinscheduler --platform linux/amd64 .
	docker push hub.hmf.xyz/base/dolphinscheduler-baseos:8

emr-dsp-kdc-server:
	docker buildx build -t hub.hmf.xyz/base/emr-dsp-kdc-server:8 -f Dockerfile-emr-dsp-kdc-server --platform linux/amd64 .
	docker push hub.hmf.xyz/base/emr-dsp-kdc-server:8

emr-dsp-kerberos-client:
	docker buildx build -t hub.hmf.xyz/base/emr-dsp-kerberos-client:8 -f Dockerfile-emr-dsp-kerberos-client --platform linux/amd64 .
	docker push hub.hmf.xyz/base/emr-dsp-kerberos-client:8
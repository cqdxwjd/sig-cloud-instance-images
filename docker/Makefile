hmf-centos-8:
	docker buildx build -t hub.hmf.xyz/base/hmf-centos:8 --platform linux/amd64 .
	docker push hub.hmf.xyz/base/hmf-centos:8

dolphinscheduler-baseos:
	docker buildx build -t hub.hmf.xyz/base/dolphinscheduler-baseos:8 -f Dockerfile-dolphinscheduler --platform linux/amd64 .
	docker push hub.hmf.xyz/base/dolphinscheduler-baseos:8

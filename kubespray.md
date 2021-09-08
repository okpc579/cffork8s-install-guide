kubespray 용 cffork8s 설치가이드~~

다음 가이드는 PaaS-TA Continaer-Platform 단독 배포 시 사용되는 kubespray 기반의 cffork8s 설치가이드이다~~

1. 문서 개요  
1.1. 목적  
어쩌구~~

1.2. 범위  
어쩌구~~

1.3. 참고자료
어쩌구~~




2. kubespray 설치  
2.1. aws 기반 설치
기본적으로 가이드를 따라가되 어쩌구~~~
주의사항 (aws시 인셉션 구성시 IAM을 추가하고 태그를 단다.)
cp 단독가이드 2.5. Kubespray 파일 수정 진행~~~
2.6. Kubespray 설치에서 $ ansible-playbook -i inventory/mycluster/hosts.yaml  --become --become-user=root cluster.yml
해당 명령어 실행전에 nodelocaldns false, nginxingress false 해주고 cloud_provider:에 aws를 추가한다.
그리고 실행~~

2.2. openstack 기반 설치
기본적으로 가이드를 따라가되 어쩌구~~~
cp 단독가이드 2.5. Kubespray 파일 수정 진행~~~
2.6. Kubespray 설치에서 $ ansible-playbook -i inventory/mycluster/hosts.yaml  --become --become-user=root cluster.yml
해당 명령어 실행전에 nodelocaldns false, nginxingress false 해주고
그리고 실행~~


3. cffork8s 설치
3.1. Prerequisite 

version은~~~~  
util~~~~

3.2. 실행파일 소개

어쩌구~~


3.3. storageclass 

어쩌구~~

3.4. variable 생성

어쩌구~~

3.5. rendred

어쩌구~~

3.6. 설치~~~

어쩌구~~

3.7. (참고) 삭제~~~~




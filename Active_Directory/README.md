# Active Directory의 기본기를 배우기 위한 실습

Microsoft Official Course인 20742를 수료하며 배운 내용을 정리한 내용이다.

# VM 환경

|Virtual Machine|Role|
|:---|:---:|
|LON-DC1|Domain Controller in the Adatum.com domain|
|TOR-DC1|Domain Controller in the Adatum.com domain (in another site)|
|TREY-DC1|Domain controller in Treyresearch.com domain|
|LON-SVR1|Member server in the Adatum.com domain|
|LON-SVR2|Member server in the Adatum.com domain with Web server role|
|CA-SVR1|Server not joined to the domain to be used as offline root CA|
|LON-CL1|Windows 10 client wth Microsoft office 2016 installed|
|LON-CL2|Windows 10 client wth office 2016 installed|


# 목차

## 1. Deploying AD DS
    * 멤버 서버에 AD Domain Service를 설치 후에 기존 도메인의 DC서버로 승격을 목표로 한다.

## 2. Deploying domain controllers by performing domain controller cloning
    * Hyper-v VM 추출을 통한 DC 복제

## 3. Administering AD DS
    * AD 관리 센터를 사용하여서 Object를 쉽게 컨트롤 할 수 있다.

## 4. Creating and managing groups in AD DS
    * AD Domain Service를 사용하여 그룹을 생성하고 관리한다.

## 5. Creating and configuring user accounts in AD DS
    * User 생성을 좀 더 쉽게하기 위하여 User Template을 작성한다.
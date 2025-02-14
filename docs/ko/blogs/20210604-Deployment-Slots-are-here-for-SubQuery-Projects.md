# SubQuery 프로젝트용 배포 슬롯이 있습니다.

> 오늘 우리는 SubQuery의 호스팅 서비스에서 개발자 경험을 향상시키는 완전히 새로운 기능인 배포 슬롯을 소개합니다.

[SubQuery 프로젝트](https://project.subquery.network/)는 체인 탐색기, 지갑, NFT 탐색기 등 많은 프로젝트에서 이미 관리 및 호스팅 서비스로 사용되고 있습니다. 고객이 신뢰하고 사용하는 서비스입니다.

![](https://miro.medium.com/max/1400/0*PugDgh6weZspRIO2)

이제 격리된 스테이징 슬롯에 배포할 수 있습니다.

항상 SubQuery의 인프라를 직접 실행할 수 있지만(자체 노드 및 쿼리 서비스를 사용하여), 우리는 호스팅 서비스를 Polkadot/Substrate 에코시스템에서 가장 안정적이고 탄력적이며 성능이 뛰어난 데이터 공급자로 만드는 것을 목표로 합니다.

[SubQuery 프로젝트](https://project.subquery.network/)의 작성자는 자신의 프로젝트와 해당 프로젝트 내의 데이터를 지속적으로 개선하고 업데이트합니다. 유감스럽게도 주요 변경 사항이 발생한 경우 체인 데이터를 다시 색인화하는 데 며칠은 아니더라도 몇 시간이 걸립니다. 궁극적으로 우리의 목표는 귀하가 프로젝트를 업데이트하고, 데이터를 다시 색인화하며, 호스팅된 SubQuery 프로젝트를 **다운타임 없이** 업그레이드할 수 있도록 하는 것입니다. >

**이것이 바로 배포 슬롯이 해결하는 것입니다.**

![](https://miro.medium.com/max/1400/0*vQ33aqhn1eVllo5t)

스테이징 슬롯은 기본 프로덕션 슬롯과 독립적으로 실행됩니다.

[호스팅된 서비스의 SubQuery 프로젝트](https://project.subquery.network/)에 대한 새 배포를 만들 때 프로덕션 또는 스테이징 슬롯에 배포하도록 선택할 수 있습니다. 이 두 슬롯은 격리된 환경이며 각각 자체 데이터베이스가 있고 독립적으로 동기화됩니다. 스테이징 슬롯이 시작되고 인덱싱이 완료되면 가동 중지 시간 없이 프로덕션으로 승격할 수 있습니다.

스테이징 슬롯은 다음에 적합합니다.

-   별도의 환경에서 SubQuery 프로젝트에 대한 변경 사항을 검증합니다. 스테이징 슬롯에는 dApp에서 사용할 수 있는 프로덕션에 대한 다른 URL이 있습니다.
-   업데이트된 SubQuery 프로젝트에 대한 데이터 워밍업 및 인덱싱을 통해 dApp의 다운타임 제거
-   공개적으로 노출하지 않고 SubQuery 프로젝트에 대한 새 릴리스를 준비합니다. 스테이징 슬롯은 Explorer에서 공개적으로 표시되지 않으며 나만 볼 수 있는 고유한 URL이 있습니다.

이제 [SubQuery 프로젝트](https://project.subquery.network/)에서 직접 시도해 볼 수 있습니다.
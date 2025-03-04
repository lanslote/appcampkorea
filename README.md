---
title: Welcome to App Camp, New Adventure!
author: Jeongwoo Choi
date: 2024-01-01
layout: home
permalink: /
---

<img src="./assets/microsoftteams_appcamp-webheader3.png" style="width: 100%; float: right;" />

<hr />

App Camp: New Adventure는 Build 2023에서 열리는 이번 세션을 위해 특별히 만들어진 Teams App Camp의 새로운 실습 세트입니다:

 * [**Build Microsoft Teams apps leveraging existing software investments**](https://build.microsoft.com/en-US/sessions/358b48ba-2608-41a5-a204-53f6f974f30f?source=/schedule){:target="_blank"} (pre-day workshop)
 * [**From Web Services to Teams Apps using Teams Toolkit v5.0**](https://build.microsoft.com/en-US/sessions/e5152be8-46ae-4b51-8c18-6b01416cb261?source=/schedule){:target="_blank"} (hands-on lab)

앱 캠프의 진정한 정신에 따라, 물론 랩은 오픈 소스이기 때문에 컨퍼런스가 끝난 후에도 누구나 즐길 수 있습니다. 피드백과 참여는 언제나 감사합니다! 피드백과 함께 [깃허브에 이슈를 추가](https://github.com/microsoft/app-camp/issues/new?labels=new%20labs){:target="_blank"} 해주시거나 저희에게 직접 연락해 주세요. 감사합니다!

> #### Here are the labs
>
> * [**Lab 1 - Create your first app with Teams Toolkit**](./hol/2024-01-02-1.create-app.html) 이 랩에서는 Teams Toolkit을 설정하고 Teams 메시지 확장을 만드는 방법을 알아보겠습니다.
> * [**Lab 2 - Integrate business data with your application**](./hol/2024-01-03-2.integrate-web-service.html) 이 실습에서는 새로운 앱을 'Northwind Suppliers’라고 브랜딩하고, Microsoft Teams 대화에서 Northwind Traders 샘플 데이터베이스의 데이터를 삽입할 수 있는 기능을 제공합니다. 또한 메시지 확장을 사용하여 어댑티브 카드를 생성하고 전송하는 방법을 배우게 됩니다.
> * [**Lab 3 - Add link unfurling**](./hol/2024-01-04-3.add-link-unfurling.html) 이 랩에서는 사용자가 대화에 URL을 포함할 때 사용자 정의 요약을 제공하는 링크 언퍼링 기능을 사용하는 방법을 배우게 됩니다.
> * [**Lab 4 - Action message extensions with Open AI**](./hol/2024-01-05-4.add-ai.html) 이 랩에서는 “액션” 메시지 확장 기능을 만드는 방법을 배울 수 있습니다. 이 기능은 직접 실행하거나 다른 팀 메시지의 컨텍스트 메뉴에서 실행하여 해당 메시지에 대한 작업을 수행할 수 있습니다. 이 랩에서는 Open AI 상업 웹 서비스(Azure 또는 Open AI 계정을 사용하여)를 이용하여 메시지를 생성합니다.
> * [**Lab 5 - Single Sign-on and Microsoft Graph**](./hol/2024-01-06-5.add-sso.html) 이 실습에서는 Azure AD Single Sign-On을 사용하여 사용자를 인증하고 Microsoft Graph API를 호출하는 방법을 배웁니다. 이와 같은 과정은 로그인한 사용자를 대신하여 Azure AD로 보호되는 웹 서비스를 호출할 때 사용됩니다.
> * [**Lab 6 - Run the app in Outlook**](./hol/2024-01-07-6.run-in-outlook.html) 이 랩에서는 Microsoft Outlook에서 Northwind Suppliers 애플리케이션을 실행합니다.
{: .block-tip }

<a href="./hol/2024-01-02-1.create-app.html">
  <img src="./assets/new-adventure/arrow-start-here.png" style="width: 20%">
</a>

Lab 1부터 시작해보세요. 이 곳에서는 Teams Toolkit을 설치하고, Teams에서 사용할 수 있는 메시지 확장 기능을 만들어봅니다.

## App Camp at Build 2023

Build 세션의 제목과 요약은 다음과 같습니다:

### Build Microsoft Teams apps leveraging existing software investments

_마이크로소프트 팀즈가 협업 도구뿐만 아니라 협업 애플리케이션을 구축할 수 있는 플랫폼임은 이미 알고 계실 것입니다. 하지만 팀즈는 기존의 웹 애플리케이션과 서비스를 확장할 수 있도록 설계되었다는 사실은 잘 모르실 수도 있습니다. 팀즈 앱을 제공하면 사용자 경험을 간소화하고, 사용자가 마이크로소프트 365에서 매일 작업하는 동안 앱으로 유입시킬 수 있습니다. 이 실습 워크샵에서는 기존의 웹 페이지, REST API, 그리고 OpenAI 인공지능 서비스를 기반으로 팀즈 앱을 만들어 보게 됩니다. 팀즈 앱이 내부적으로 어떻게 작동하는지, 그리고 팀즈 툴킷이 개발 과정을 어떻게 가속화하는지 배울 수 있습니다. 저희와 함께하셔서 기업용이나 ISV용 앱을 마이크로소프트 팀즈로 가져오는 과정을 시작해보세요!_

이 실습은 하루 종일 진행되는 워크숍의 주요 내용입니다. 학생들은 App Camp 실습 [A-01, A-02, A-03](https://microsoft.github.io/app-camp/#path-a-start-with-azure-ad){:target="_blank"} 을 통해 웹 기반 애플리케이션을 Microsoft Teams의 탭으로 재사용하는 방법을 배울 것입니다. 또한 새로운 [Extend](https://microsoft.github.io/app-camp/aad/ExtendTeamsApp/){:target="_blank"} 실습을 시도해보고, 이 페이지들을 Microsoft Outlook과 Microsoft 365 홈페이지에 표시하는 방법을 알아볼 수 있습니다.

### From Web Services to Teams Apps using Teams Toolkit v5.0

_이 실습에서는 Microsoft Teams와 Outlook을 위한 애플리케이션을 개발하여 비즈니스 데이터를 채팅과 이메일로 가져올 수 있는 방법을 배웁니다. 이 애플리케이션은 엔터프라이즈와 상업적인 REST 서비스에 기반하여 만들어졌습니다. 이 서비스들은 현재 컴퓨팅 환경에서 매우 흔하게 사용되고 있습니다. 이를 통해 사용자들은 비즈니스 상황을 공유하고, 수신자들을 애플리케이션의 상황에 맞게 바로 연결할 수 있습니다. 새로운 버전의 Teams Toolkit은 이 과정을 쉽게 도와줍니다! 개발 능력을 향상시키고 조직의 생산성을 높이는 강력한 Teams 애플리케이션을 만들 수 있는 이 기회를 놓치지 마세요._

이 시리즈의 1-4번까지의 실습을 체험할 수 있는 1시간짜리 핸즈온 랩입니다.

<h1>전기재해 모니터링 및 노후시설 AS 신고 관리 시스템</h1>

<h2>프로젝트 소개</h2>
<p>전기 재해 모니터링과 노후시설 AS 관리를 통합한 웹 기반 시스템입니다. Spring Framework를 기반으로 개발되었으며, Python과 Java를 연동하여 실시간 데이터 분석 및 시각화 기능을 제공합니다</p>

<h2>주요 기능</h2>
<ol>
  <li>전기 재해 모니터링 대시보드
    <ul>
      <li>전국 지역별 전기화재 발생 현황 실시간 모니터링</li>
      <li>Chart.js를 활용한 통계 차트 구현</li>
      <li>지역별 발화요인 및 피해규모 분석 기능</li>
    </ul>
  </li>
  <li>노후시설 A/S 신고 관리 시스템
    <ul>
      <li>사용자 권한 관리
        <ul>
          <li>일반 사용자/엔지니어/관리자 역할 구분</li>
          <li>세션/쿠키 기반 보안 인증</li>
        </ul>
      </li>
      <li>A/S 접수
        <ul>
          <li>시설물 유형별 AS 신청 접수</li>
          <li>실시간 처리현황 모니터링</li>
          <li>예약 시간대 자동 관리 시스템</li>
        </ul>
      </li>
      <li>작업 관리
        <ul>
          <li>엔지니어 자동 배정 알고리즘</li>
          <li>실시간 작업 상태 추적</li>
          <li>AS 이력 관리 및 통계 분석</li>
        </ul>
      </li>
    </ul>
  </li>
</ol>

<h2>기술 스택</h2>
<ol>
  <li>Backend
    <ul>
      <li>Spring MVC Framework</li>
      <li>MyBatis</li>
      <li>MySQL</li>
      <li>Java 11</li>
      <li>Python (데이터 분석/예측)</li>
    </ul>
  </li>
  <li>Frontend
    <ul>
      <li>Thymeleaf</li>
      <li>JavaScript/jQuery</li>
      <li>Chart.js</li>
      <li>Bootstrap 5</li>
    </ul>
  </li>
  <li>개발 도구
    <ul>
      <li>IDE: VS Code (Spring Boot Extension)</li>
      <li>빌드 도구: Maven</li>
      <li>형상 관리: Git/GitHub</li>
    </ul>
  </li>
</ol>

<h2>주요 구현 사항</h2>
<ol>
  <li>데이터 처리 및 분석
    <ul>
      <li>Python-Java 연동을 통한 실시간 데이터 분석</li>
      <li>RESTful API 기반 데이터 통신</li>
      <li>MyBatis를 활용한 효율적인 데이터베이스 관리</li>
    </ul>
  </li>
  <li>사용자 인터페이스
    <ul>
      <li>반응형 웹 디자인 구현</li>
      <li>실시간 데이터 시각화</li>
      <li>직관적인 사용자 경험 제공</li>
    </ul>
  </li>
  <li>시스템 아키텍처
    <ul>
      <li>MVC 패턴 기반 설계</li>
      <li>모듈화된 컴포넌트 구조</li>
      <li>확장 가능한 시스템 설계</li>
    </ul>
  </li>
</ol>

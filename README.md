<div align="center" style="background-color: #8C1D40; padding: 30px; border-radius: 10px; margin-bottom: 20px;">
  <h1 style="color: #ffffff; margin: 0; font-size: 32px;">🍚 밥메이트 (Bob-Mate)</h1>
  <p style="color: #ffccd5; margin: 10px 0 0 0; font-size: 16px;">캠퍼스 밥약 매칭 플랫폼 PRD</p>
  <p style="color: #ffffff; font-size: 14px; opacity: 0.9;">안전한 학교 이메일 인증 기반 식사 매칭 서비스</p>
</div>

---

## 📌 01 제품 개요
<div style="background-color: #fdf2f4; border-left: 5px solid #8C1D40; padding: 15px; border-radius: 4px; margin-bottom: 20px;">
  <p><strong>• 서비스 정의:</strong> 처음 보는 타과 학생이나 선후배와 부담 없이 밥약을 잡을 수 있는 캠퍼스 매칭 플랫폼</p>
  <p><strong>• 학교 이메일 인증:</strong> 학교 이메일 인증을 통해 검증된 학생들끼리만 안전하게 매칭되는 시스템 (@korea.ac.kr)</p>
  <p><strong>• 공강 시간 활용:</strong> 공강 시간을 활용하여 같은 캠퍼스 내 학생들과 식사 약속을 연결하는 서비스</p>
</div>

## 👤 02 유저 인증 및 프로필
* **학교 이메일 인증 기능**
  * 학교 메일 주소 입력 <code style="color: #8C1D40; background-color: #fdf2f4; padding: 2px 6px; border-radius: 4px;">예: @korea.ac.kr</code>
  * 6자리 인증 코드 발송 및 확인 (3분 이내 입력 제한으로 보안 강화)
* **프로필 설정**
  * 단과대 및 전공 학과 선택
  * 학번 정보 입력 (예: 25학번, 26학번)
  * MBTI 4자리 선택하여 성향 표시
  * 학과, 학번, MBTI 정보를 매칭 알고리즘에 활용하며, 향후 매칭 시 상대방에게 공개되는 기본 정보로 활용

## 📅 03 밥약 개설 기능
* **약속 시간 및 장소**
  * 캘린더에서 원하는 날짜 선택 및 점심/저녁 시간대를 30분 단위로 세부 설정
  * 학교 근처 식당 이름 직접 입력 또는 지도 API 연동하여 식당 위치 검색 후 약속 장소 정보 등록
* **정산 방식 선택 <span style="background-color: #ef4444; color: white; padding: 2px 6px; font-size: 11px; border-radius: 4px; font-weight: bold;">필수</span>**
  * 각자 계산 (더치페이)
  * 내가 쏨
  * 만나서 조율

## 🤝 04 매칭 완료 및 이행
* **방장의 수락/거절:** 신청자의 학과, 학번, MBTI 확인 후 수락 시 매칭 확정 (모임 인원수 자동 업데이트)
* **앱 내 디엠 채팅:** 연락처 비공개 임시 채팅방 오픈으로 전화번호나 카카오톡 ID 교환 불필요 (만나서 직접 연락처 교환 유도)
* **약속 리마인더:** 약속 시간 1시간 전 자동 알림 및 '오늘 약속이 있습니다!' 팝업으로 시스템 지원
* **노쇼 신고 시스템:** 약속 시간 이후 신고 버튼 활성화 및 노쇼 횟수 데이터 누적을 통해 향후 매칭 점수에 패널티 부여

## 📊 05 데이터 구조
<table style="width: 100%; border-collapse: collapse; margin-top: 10px;">
  <tr style="background-color: #8C1D40; color: white;">
    <th style="padding: 10px; border: 1px solid #dee2e6; text-align: left;">데이터 유형</th>
    <th style="padding: 10px; border: 1px solid #dee2e6; text-align: left;">포함 항목</th>
  </tr>
  <tr>
    <td style="padding: 10px; border: 1px solid #dee2e6; font-weight: bold;">유저 데이터</td>
    <td style="padding: 10px; border: 1px solid #dee2e6;">이메일, 학과, 학번, MBTI, 노쇼 횟수</td>
  </tr>
  <tr style="background-color: #f9f9f9;">
    <td style="padding: 10px; border: 1px solid #dee2e6; font-weight: bold;">밥약 방 데이터</td>
    <td style="padding: 10px; border: 1px solid #dee2e6;">방장, 날짜, 시간, 식당, 정산방식, 모집상태</td>
  </tr>
</table>

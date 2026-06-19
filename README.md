<div style="display: flex; flex-wrap: wrap; gap: 20px; font-family: 'Malgun Gothic', sans-serif; color: #333; background-color: #FAFAFA; padding: 15px; border-radius: 12px;">

  <div style="flex: 1; min-width: 320px; padding: 15px; background-color: #ffffff; border-radius: 10px; border: 1px solid #E0E0E0;">
    
    <div style="background: linear-gradient(135deg, #8C1D40 60%, #A3E2A4 100%); padding: 25px; border-radius: 8px; color: white; margin-bottom: 25px; box-shadow: 0 4px 10px rgba(0,0,0,0.05);">
      <h1 style="color: white; margin: 0; font-size: 26px; letter-spacing: -1px;">🍚 밥메이트 (Bob-Mate)</h1>
      <p style="margin: 8px 0 0 0; font-size: 14px; color: #FFCCD5; font-weight: bold;">캠퍼스 밥약 매칭 플랫폼 PRD</p>
      <div style="margin-top: 10px; font-size: 12px; background-color: rgba(255,255,255,0.2); padding: 4px 8px; border-radius: 4px; display: inline-block;">🌱 새 학기 맞이 소프트웨어 프로젝트</div>
    </div>

    <h2 style="border-left: 4px solid #8C1D40; padding-left: 10px; color: #8C1D40; font-size: 18px;">📌 01 제품 개요</h2>
    <p style="font-size: 13px; line-height: 1.6;">• 처음 보는 타과 학생이나 선후배와 부담 없이 밥약을 잡을 수 있는 캠퍼스 매칭 플랫폼</p>
    <p style="font-size: 13px; line-height: 1.6;">• <strong>학교 이메일 인증:</strong> 학교 이메일 인증을 통해 검증된 학생들끼리만 안전하게 매칭되는 시스템 (@korea.ac.kr)</p>
    <p style="font-size: 13px; line-height: 1.6;">• <strong>공강 시간 활용:</strong> 공강 시간을 활용하여 같은 캠퍼스 내 학생들과 식사 약속을 연결하는 서비스</p>

    <h2 style="border-left: 4px solid #8C1D40; padding-left: 10px; color: #8C1D40; font-size: 18px;">👤 02 유저 인증 및 프로필</h2>
    <ul style="font-size: 13px; line-height: 1.6; padding-left: 20px;">
      <li><strong>학교 이메일 인증 기능:</strong> 학교 메일 주소 입력 및 6자리 인증 코드 발송 (3분 이내 입력 제한으로 보안 강화)</li>
      <li><strong>프로필 데이터 관리:</strong> 학과, 학번, MBTI 정보를 매칭 알고리즘에 활용하며, 향후 매칭 시 상대방에게 공개되는 기본 정보로 활용</li>
    </ul>

    <h2 style="border-left: 4px solid #8C1D40; padding-left: 10px; color: #8C1D40; font-size: 18px;">📅 03 밥약 개설 기능</h2>
    <ul style="font-size: 13px; line-height: 1.6; padding-left: 20px;">
      <li><strong>약속 시간 및 장소:</strong> 캘린더 날짜 선택 및 점심/저녁 시간대 30분 단위 세부 설정, 지도 API 연동 식당 위치 검색</li>
      <li><strong>정산 방식 선택 (필수):</strong> 각자 계산 (더치페이) / 내가 쏨 / 만나서 조율 중 선택하여 방 정보에 표시</li>
    </ul>

    <h2 style="border-left: 4px solid #8C1D40; padding-left: 10px; color: #8C1D40; font-size: 18px;">🤝 04 매칭 완료 및 이행</h2>
    <ul style="font-size: 13px; line-height: 1.6; padding-left: 20px;">
      <li><strong>방장의 수락/거절:</strong> 신청자의 학과, 학번, MBTI 확인 후 수락 시 매칭 확정 및 인원수 자동 업데이트</li>
      <li><strong>앱 내 디엠 채팅:</strong> 연락처 비공개 임시 채팅방 오픈으로 개인정보를 보호하며 오프라인 만남 유도</li>
      <li><strong>노쇼 신고 시스템:</strong> 약속 시간 이후 신고 기능 활성화 및 노쇼 데이터 누적을 통한 패널티 부여</li>
    </ul>

    <h2 style="border-left: 4px solid #8C1D40; padding-left: 10px; color: #8C1D40; font-size: 18px;">📊 05 데이터 구조</h2>
    <table style="width: 100%; border-collapse: collapse; margin-top: 10px; font-size: 13px;">
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
  </div>

  <div style="flex: 1; min-width: 340px; display: flex; justify-content: center; align-items: center; background-color: #E8F5E9; padding: 20px; border-radius: 12px; border: 2px dashed #A3E2A4;">
    
    <div style="width: 340px; height: 660px; background-color: #2D3748; border-radius: 36px; padding: 12px; box-shadow: 0 12px 30px rgba(140,29,64,0.15); box-sizing: border-box;">
      
      <div style="width: 100%; height: 100%; background-color: white; border-radius: 26px; overflow: hidden; display: flex; flex-direction: column; font-size: 13px; position: relative;">
        
        <div style="background-color: #8C1D40; color: white; padding: 18px 15px 12px; text-align: center; font-weight: bold; font-size: 16px; letter-spacing: 1px;">
          밥메이트 <span style="font-size: 12px; color: #FFF9C4; font-weight: normal;">[고려대]</span> 🍚
        </div>

        <div id="step1" style="padding: 15px; display: flex; flex-direction: column; height: 100%; box-sizing: border-box; background: linear-gradient(to bottom, #FFFDE7 0%, #FFFFFF 20%);">
          <h3 style="margin-top: 0; color: #8C1D40; font-size: 14px; border-bottom: 2px solid #8C1D40; padding-bottom: 5px;">[1단계] 학교 인증 및 프로필 설정</h3>
          
          <label style="font-weight: bold; margin: 8px 0 3px; display: block; color: #555;">학교 이메일</label>
          <input type="text" id="in-email" value="tiger@korea.ac.kr" style="width: 100%; padding: 8px; border: 1px solid #CCC; border-radius: 4px; box-sizing: border-box; font-size: 12px;">
          
          <label style="font-weight: bold; margin: 8px 0 3px; display: block; color: #555;">학과 (전공)</label>
          <input type="text" id="in-dept" value="사회학과" style="width: 100%; padding: 8px; border: 1px solid #CCC; border-radius: 4px; box-sizing: border-box; font-size: 12px;">
          
          <label style="font-weight: bold; margin: 8px 0 3px; display: block; color: #555;">학번 선택</label>
          <select id="in-year" style="width: 100%; padding: 8px; border: 1px solid #CCC; border-radius: 4px; box-sizing: border-box; font-size: 12px;">
            <option value="26학번" selected>26학번 (새내기)</option>
            <option value="25학번">25학번</option>
            <option value="24학번 이전">24학번 이전</option>
          </select>

          <label style="font-weight: bold; margin: 8px 0 3px; display: block; color: #555;">MBTI 성향</label>
          <input type="text" id="in-mbti" value="ENFP" style="width: 100%; padding: 8px; border: 1px solid #CCC; border-radius: 4px; box-sizing: border-box; font-size: 12px;">

          <button onclick="document.getElementById('step1').style.display='none'; document.getElementById('step2').style.display='flex';" style="background-color: #8C1D40; color: white; border: none; padding: 12px; border-radius: 6px; font-weight: bold; cursor: pointer; width: 100%; margin-top: auto; font-size: 13px; box-shadow: 0 3px 6px rgba(140,29,64,0.2);">새 학기 밥약 시작하기 🌱</button>
        </div>

        <div id="step2" style="padding: 15px; display: none; flex-direction: column; height: 100%; box-sizing: border-box;">
          <h3 style="margin-top: 0; color: #8C1D40; font-size: 14px; border-bottom: 2px solid #8C1D40; padding-bottom: 5px;">[2단계] 캠퍼스 밥약 방 선택</h3>
          
          <div onclick="document.getElementById('partner-text').innerText='경영학과 25학번 (ISTJ) / 매칭 장소: 정문 서브웨이'; document.getElementById('step2').style.display='none'; document.getElementById('step4').style.display='flex';" style="border: 1px solid #E0E0E0; padding: 12px; border-radius: 8px; background-color: #FFF; margin-bottom: 12px; cursor: pointer; box-shadow: 0 2px 4px rgba(0,0,0,0.04); border-left: 4px solid #A3E2A4;">
            <div style="font-weight: bold; font-size: 13px; color: #111;">Subway에서 같이 점심 먹을 새내기 구함!</div>
            <div style="font-size: 11px; color: #666; margin-top: 5px;">📍 정문 서브웨이 | ⏰ 12:00 | 💰 각자 계산</div>
            <div style="text-align: right; font-size: 11px; color: #8C1D40; font-weight: bold; margin-top: 8px;">👉 신청하기 (클릭)</div>
          </div>

          <div id="new-room-area"></div>

          <button onclick="document.getElementById('step2').style.display='none'; document.getElementById('step3').style.display='flex';" style="background-color: #2D3748; color: white; border: none; padding: 12px; border-radius: 6px; font-weight: bold; cursor: pointer; width: 100%; margin-top: auto; font-size: 12px;">＋ 내가 직접 밥약 방 개설하기</button>
        </div>

        <div id="step3" style="padding: 15px; display: none; flex-direction: column; height: 100%; box-sizing: border-box;">
          <h3 style="margin-top: 0; color: #8C1D40; font-size: 14px; border-bottom: 2px solid #8C1D40; padding-bottom: 5px;">[3단계] 새로운 밥약 방 개설</h3>
          
          <label style="font-weight: bold; margin: 10px 0 3px; display: block; color: #555;">약속 시간 설정</label>
          <input type="text" id="room-time" value="12:30" style="width: 100%; padding: 8px; border: 1px solid #CCC; border-radius: 4px; box-sizing: border-box;">

          <label style="font-weight: bold; margin: 10px 0 3px; display: block; color: #555;">식당 위치 입력</label>
          <input type="text" id="room-loc" value="안암역 미소야" style="width: 100%; padding: 8px; border: 1px solid #CCC; border-radius: 4px; box-sizing: border-box;">

          <label style="font-weight: bold; margin: 10px 0 3px; display: block; color: #555;">정산 방식 선택</label>
          <select id="room-pay" style="width: 100%; padding: 8px; border: 1px solid #CCC; border-radius: 4px; box-sizing: border-box;">
            <option value="각자 계산 (더치페이)">각자 계산 (더치페이)</option>
            <option value="내가 쏨">내가 쏨 💸</option>
            <option value="만

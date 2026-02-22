<div align="center">
  <!-- HEADER SECTION -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,100:92FE9D&height=250&section=header&text=Kwanjoon%20Park&fontSize=70&animation=fadeIn&fontAlignY=38&desc=Robotics%20Software%20Engineer%20%7C%20Bridging%20Sim-to-Real&descAlignY=55&descAlign=50" alt="header" width="100%" />

  <h3>🚀 "로봇에게 세상을 보는 눈(Vision)을 선물합니다."</h3>
  <p>
    <b>산업용 로봇 비전(Perception)</b>과 <b>합성 데이터(Synthetic Data)</b> 파이프라인 구축에 강점이 있는 엔지니어입니다.<br>
    불확실한 환경에서도 강건한 <b>6-DoF Pose Estimation</b> 시스템을 설계하고 구현합니다.
  </p>

  <!-- TECH STACK BADGES -->
  <br>
  <img src="https://img.shields.io/badge/Tech_Stack-Main_Skill-black?style=for-the-badge"/>
  <br>
  <div style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap;">
    <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
    <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white"/>
    <img src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white"/>
    <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
    <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
    <img src="https://img.shields.io/badge/RealSense-0071C5?style=flat-square&logo=intel&logoColor=white"/>
    <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
    <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  </div>
</div>

<br>

<!-- EXPERIENCE SECTION (Timeline Style) -->
<h2 align="center">⚡ Professional Experience</h2>
<div align="center">
  <table style="width: 100%; border: none;">
    <tr>
      <td width="15%" align="center" valign="top">
        <img src="https://img.shields.io/badge/2026.01%20--%20Present-ETRI-blue?style=for-the-badge&logo=electron" />
      </td>
      <td width="85%" align="left">
        <h3>🤖 ETRI (한국전자통신연구원) 에너지지능화연구실</h3>
        <p><b>Role: Research Intern (연구연수생)</b></p>
        <ul>
          <li><b>Project:</b> 로봇 조작을 위한 산업용 객체(VCB 패널) 6-DoF Pose Estimation</li>
          <li><b>Key Achievement:</b> 데이터 부족 문제 해결을 위한 <b>자체 합성 데이터 파이프라인(Synthetic Data Pipeline)</b> 구축</li>
          <li><b>Algorithm:</b> <code>Geometry-Aware Background Segmentation</code> 개발
            <ul>
              <li>Canny Edge → FloodFill → ConvexHull 알고리즘을 결합하여 수동 라벨링 없이 Ground Truth 자동 생성</li>
              <li>ArUco 마커 기반 PnP 알고리즘 역설계를 통한 6D Pose 데이터셋 자동화</li>
            </ul>
          </li>
          <li><b>Tech:</b> ROS(Noetic), OpenCV, RealSense D455, ChArUco Board</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td align="center" valign="top">
        <img src="https://img.shields.io/badge/2022%20--%202024-ROK_NAVY-navy?style=for-the-badge&logo=ferrari" />
      </td>
      <td align="left">
        <h3>⚓ 대한민국 해군 (Republic of Korea Navy)</h3>
        <p><b>Role: SW Development Sergeant (SW 개발병)</b></p>
        <ul>
          <li><b>System Security:</b> 폐쇄망(Closed Network) 환경에서의 국방 SW 시스템 개발 및 유지보수</li>
          <li><b>Optimization:</b> 군수 관리 시스템 DB 쿼리 최적화로 데이터 조회 속도 20% 개선</li>
          <li><b>Reliability:</b> 국가 안보와 직결된 시스템의 무중단 운영 및 트러블 슈팅 경험</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

<br>

<!-- HIGHLIGHT PROJECT (Infographic Style Card) -->
<h2 align="center">🔥 Highlight Project: ETRI 6-DoF Pipeline</h2>
<div align="center">
  <table style="border: 1px solid #e1e4e8; border-radius: 10px; width: 90%;">
    <thead align="center">
      <tr>
        <th colspan="3"><h3>Robust Synthetic Data Generation Pipeline</h3></th>
      </tr>
    </thead>
    <tbody align="center">
      <tr>
        <td width="30%">
          <b>Step 1. Acquisition</b><br><br>
          <img src="https://img.shields.io/badge/Input-RGB_Image-lightgrey"/><br>
          RealSense D455<br>+ ArUco Board
        </td>
        <td width="5%">➡️</td>
        <td width="30%">
          <b>Step 2. Processing</b><br><br>
          <img src="https://img.shields.io/badge/Algorithm-Geometry_Aware-orange"/><br>
          Canny Edge + FloodFill<br>+ ConvexHull
        </td>
        <td width="5%">➡️</td>
        <td width="30%">
          <b>Step 3. Output</b><br><br>
          <img src="https://img.shields.io/badge/Result-6D_Pose_GT-success"/><br>
          Background-Free Data<br>Ready for Sim-to-Real
        </td>
      </tr>
      <tr>
        <td colspan="5" align="left" style="padding: 20px;">
          <blockquote>
            "기존의 단순 마커 기반 학습은 조명 변화와 가려짐(Occlusion)에 취약했습니다.<br>
            저는 <b>기하학적 특성(Geometry)</b>을 활용한 세그멘테이션 알고리즘을 직접 구현하여,<br>
            수동 라벨링 없이도 실제 공장 환경에서 강건한 고품질 데이터셋을 생성하는 파이프라인을 완성했습니다."
          </blockquote>
        </td>
      </tr>
    </tbody>
  </table>
</div>

<br>

<!-- AWARDS SECTION -->
<h2 align="center">🏆 Honors & Awards</h2>
<div align="center">
  <table style="width: 100%;">
    <tr>
      <td width="10%" align="center">🥇</td>
      <td width="90%">
        <b>Grand Prize (1st Place), GIST AI Hackathon</b><br>
        <i>Gwangju Institute of Science and Technology (GIST)</i><br>
        - AI 모델링 및 시스템 통합 팀 리드, 최적의 딥러닝 아키텍처 제안
      </td>
    </tr>
    <tr>
      <td width="10%" align="center">🎓</td>
      <td width="90%">
        <b>Academic Excellence Scholarship</b><br>
        <i>Chonnam National University</i><br>
        - GPA 3.9 / 4.5 (Major: Software Engineering)
      </td>
    </tr>
  </table>
</div>

<br>

<!-- FOOTER / CONTACT -->
<div align="center">
  <img src="https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail&link=mailto:your_email@gmail.com"/>
  <img src="https://img.shields.io/badge/Blog-Visit_Now-green?style=for-the-badge&logo=velog&link=https://velog.io/@yourid"/>
  <br><br>
  <p>© 2026 Kwanjoon Park. Engineered for Robotics.</p>
</div>

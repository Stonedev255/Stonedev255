<div align="center">

# 김영록 · Young-Rok Kim

**LiDAR SLAM · 자율주행 내비게이션 · 컴퓨터공학과 박사과정**
*LiDAR SLAM · Autonomous Navigation · Ph.D. Program in Computer Engineering*

</div>

<br>

## 👨‍🎓 About Me

<table border="0">
  <tr>
    <td valign="top">
      <details open>
        <summary><b>🇰🇷 한국어</b></summary>
        <ul>
          <li><b>이름:</b> 김영록</li>
          <li><b>소속:</b> 인제대학교 컴퓨터공학과 박사과정</li>
          <li><b>연구분야:</b> LiDAR SLAM, 자율 이동 로봇(AMR), 경로계획, 컴퓨터 비전</li>
          <li><b>이메일:</b>
            <ul>
              <li><a href="mailto:stonedev255@gmail.com">stonedev255@gmail.com</a></li>
              <li><a href="mailto:stonedev255@oasis.inje.ac.kr">stonedev255@oasis.inje.ac.kr</a> (기관)</li>
            </ul>
          </li>
        </ul>
      </details>
    </td>
    <td valign="top">
      <details open>
        <summary><b>🇺🇸 English</b></summary>
        <ul>
          <li><b>Name:</b> Young-Rok Kim</li>
          <li><b>Affiliation:</b> Inje University, Ph.D. Program in Computer Engineering</li>
          <li><b>Research areas:</b> LiDAR SLAM, autonomous mobile robots, path planning, computer vision</li>
          <li><b>Email:</b>
            <ul>
              <li><a href="mailto:stonedev255@gmail.com">stonedev255@gmail.com</a></li>
              <li><a href="mailto:stonedev255@oasis.inje.ac.kr">stonedev255@oasis.inje.ac.kr</a> (institutional)</li>
            </ul>
          </li>
        </ul>
      </details>
    </td>
  </tr>
</table>

## 🔬 Research

측위와 경로계획을 따로 두지 않고 하나의 순환으로 다룹니다. 아래 저장소는 모두 비공개이며, 자세한 내용은 메일로 문의해 주세요.
*I treat localization and path planning as one loop rather than two stages. The repositories below are private — feel free to email me for details.*

<table>
  <tr>
    <th align="left" width="22%">Project</th>
    <th align="left" width="58%">Summary</th>
    <th align="left" width="20%">Status</th>
  </tr>
  <tr>
    <td valign="top"><b>Light3D-SLAM</b><br></td>
    <td valign="top">
      KITTI Odometry에서 동작하는 <b>LiDAR 단독 SLAM</b>. 시맨틱 신뢰도로 포인트를 선별하고,
      루프 클로저에서 <b>검출과 검증을 분리</b>한 것이 핵심 명제입니다.<br>
      <sub><i>LiDAR-only SLAM on KITTI Odometry. Semantic-reliability point selection; the core claim is
      separating loop <b>detection</b> from loop <b>verification</b>.</i></sub>
    </td>
    <td valign="top">진행 중<br><sub>in progress</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>Light3D-LAPP</b></td>
    <td valign="top">
      <b>Localizability-aware 전역 경로계획</b>. 드리프트를 사후에 보정하는 대신, 측위가 잘 되는 경로로
      애초에 주행하게 만들어 경로계획이 SLAM 품질을 결정하도록 방향을 뒤집습니다.
      신뢰도 점수를 Nav2 코스트맵 레이어로 승격해 A*/Hybrid A*에 결합합니다.<br>
      <sub><i>Instead of correcting drift after the fact, plan through regions where localization holds up —
      making path planning drive SLAM quality rather than consume it.</i></sub>
    </td>
    <td valign="top">진행 중<br><sub>in progress</sub></td>
  </tr>
  <tr>
    <td valign="top"><b>PathFusion</b></td>
    <td valign="top">
      A*, RRT, RRT* 3종 이종 경로계획기의 출력을 <b>품질 기반 적응형 가중치 투표</b>로 융합하고
      통제 실험으로 검증. MovingAI 벤치마크 + 합성 환경 77개, 2,210개 시나리오, 환경 단위 분리 분할.<br>
      <sub><i>Quality-gated adaptive voting fusion over heterogeneous planners, validated on 77 environments
      and 2,210 scenarios with env-disjoint splits.</i></sub>
    </td>
    <td valign="top">진행 중<br><sub>under review</sub></td>
  </tr>
</table>

## 💻 Tech Stack

<table>
  <tr>
    <td width="33%" align="center">
      <h4>Languages</h4>
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white" />
      <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
    </td>
    <td width="33%" align="center">
      <h4>SLAM &amp; 3D</h4>
      <img src="https://img.shields.io/badge/Open3D-1E90FF?style=for-the-badge&logo=&logoColor=white" />
      <img src="https://img.shields.io/badge/GTSAM-4B0082?style=for-the-badge&logo=&logoColor=white" />
      <img src="https://img.shields.io/badge/PCL-8A2BE2?style=for-the-badge&logo=&logoColor=white" />
    </td>
    <td width="33%" align="center">
      <h4>Robotics</h4>
      <img src="https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white" />
      <img src="https://img.shields.io/badge/Nav2-2C3E50?style=for-the-badge&logo=&logoColor=white" />
      <img src="https://img.shields.io/badge/Gazebo-FF6B00?style=for-the-badge&logo=&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td width="33%" align="center">
      <h4>Deep Learning</h4>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
      <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
      <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
    </td>
    <td width="33%" align="center">
      <h4>Environment</h4>
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
    </td>
    <td width="33%" align="center">
      <h4>Datasets</h4>
      <img src="https://img.shields.io/badge/KITTI-005A9C?style=for-the-badge&logo=&logoColor=white" />
      <img src="https://img.shields.io/badge/SemanticKITTI-0072B2?style=for-the-badge&logo=&logoColor=white" />
      <img src="https://img.shields.io/badge/MovingAI-556B2F?style=for-the-badge&logo=&logoColor=white" />
    </td>
  </tr>
</table>

<sub>이전 프로젝트에서 사용: Java · Flask · TensorFlow · HTML/CSS &nbsp;·&nbsp; <i>Also used in earlier projects.</i></sub>

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Stonedev255&color=blueviolet&style=for-the-badge" alt="Profile views" />

  <h4>💫 "Making robots smarter, one line of code at a time" 💫</h4>
</div>

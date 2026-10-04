<div align="center">

<img src="docs/images/logo.png" width="112" alt="Fiction Archive logo">

# 허구기록실 · Fiction Archive

**스타레일 모드를 한곳에서, 간편하게.**  
**Organize your Star Rail mods in one place.**

Windows · XXMI / SRMI · 한국어 / English

**[다운로드 · Download](https://github.com/anjgkrhdlTwl/FictionArchive/releases/latest)** &nbsp; | &nbsp; **[문제 제보 · Report an Issue](https://github.com/anjgkrhdlTwl/FictionArchive/issues)** &nbsp; | &nbsp; **[☕ 후원 · Support](https://buymeacoffee.com/wmjh5555)**

</div>

---

## 소개

허구기록실은 **XXMI의 스타레일용 `SRMI\Mods` 폴더에 있는 모드를 관리하는 비공식 프로그램**입니다. 캐릭터별로 모드를 정리하고, 미리보기를 보면서 원하는 모드를 켜거나 끌 수 있습니다.

금빛과 남청색 테마에 미토스 배경을 더했으며, 한국어와 영어를 지원합니다.

## 주요 기능

| 기능 | 설명 |
| :--- | :--- |
| 캐릭터 분류 | 속성·운명의 길·이름으로 탐색. 속성·운명의 길 그룹 안에서는 최신 캐릭터부터 표시 |
| 개척자 관리 | 남자·여자 개척자를 나누고, 각 운명의 길별로 모드 관리 |
| 간편한 추가 | 폴더·ZIP 선택 또는 드래그 앤 드롭으로 추가 |
| 미리보기 | 정사각형 이미지와 가로 3열 카드. 활성화된 모드는 금빛 테두리로 표시 |
| 모드 켜기·끄기 | 파일을 보관한 채 활성화·비활성화 전환 |
| 토글키 확인 | 모드의 INI 파일에서 토글키를 찾아 표시 |
| 기타 모드 | UID 숨김·투명 방지·NPC·몬스터 등 별도 분류 |
| 실행·업데이트 | XXMI의 SRMI 프로필 실행 및 새 버전 확인 |
| 언어 전환 | 상단 KR / EN에서 선택하고 다음 실행에도 유지 |

## 다운로드 및 시작하기

1. **[최신 릴리스](https://github.com/anjgkrhdlTwl/FictionArchive/releases/latest)**의 **Assets**에서 `FictionArchive-…-Windows-KR-EN.zip`을 다운로드하세요.
2. ZIP 전체를 압축 해제하고 `허구기록실.exe`를 실행하세요. 실행파일과 `Assets`, `UpdateHelper.exe`를 함께 보관하세요.
3. XXMI 검색 결과에서 사용할 설치를 선택하세요. 자동 검색을 취소하거나 찾지 못한 경우, 설정에서 `XXMI Launcher.exe`와 `SRMI\Mods` 경로를 직접 선택할 수 있습니다.
4. 캐릭터를 선택한 뒤 **모드 추가**로 폴더나 ZIP을 가져오세요.
5. 사용할 모드의 **적용하기**를 누르고 **모드 실행**으로 시작하세요.

> 게임과 XXMI / SRMI는 별도로 설치해야 합니다. `update.json`은 자동 업데이트 확인용이므로 직접 다운로드할 필요가 없습니다. GitHub의 **Source code (zip)** 대신 위 이름의 배포용 ZIP을 받아 주세요.

## 모드는 어떻게 관리되나요?

실제 모드는 설정에서 연결한 **`SRMI\Mods` 폴더**에 보관됩니다. 새로 추가한 모드는 원본을 복사해 가져오며, 처음에는 비활성화됩니다.

- **적용하기:** 모드 폴더 이름의 `DISABLED_` 접두사를 제거합니다.
- **해제하기:** 폴더 이름 앞에 `DISABLED_`를 붙입니다. 파일은 그대로 남습니다.
- **삭제:** 확인 후 해당 모드 폴더를 Windows 휴지통으로 보냅니다.

**다른 모드를 켜도 이미 켜진 모드가 자동으로 꺼지지는 않습니다.** 같은 캐릭터의 모드를 추가로 켜려 하면 확인창이 표시됩니다. 하나만 사용할 때는 기존 모드를 해제한 뒤 원하는 모드를 적용하세요. 변경한 상태는 게임을 다시 실행해 반영해 주세요.

## 알아두세요

- 모드 파일은 포함되어 있지 않습니다. UID 숨김·투명 방지도 해당 모드 파일을 별도로 추가해야 합니다.
- 자동 압축 해제는 ZIP을 지원합니다. RAR·7z는 먼저 압축을 푼 뒤 폴더로 추가하세요.
- 기타 모드 분류는 Mods용 INI 모드를 관리합니다. ShaderFixes 전용 파일은 지원하지 않습니다.
- 토글키 스캔은 INI에 기록된 키를 보여줍니다. 조건이나 외부 참조에 따라 실제 동작은 달라질 수 있습니다.
- 설정과 캐릭터 지정 정보는 매니저 옆의 `Data` 폴더에 저장됩니다. 새 버전으로 옮길 때 보관해 주세요.

자세한 사용법은 다운로드한 ZIP 안의 **`README.ko.md`**를 참고하세요.

<details>
<summary><strong>English guide — click to expand</strong></summary>

## About Fiction Archive

Fiction Archive is an unofficial Honkai: Star Rail mod manager. It manages mods in **XXMI's `SRMI\Mods` folder**, with character grouping, visual previews, and controls to enable or disable each mod.

### Features

- Browse characters by Element, Path or Name. Element and Path groups list newer characters first.
- Manage male and female Trailblazers separately, with mods for each Path.
- Import folders or ZIP archives using a file picker or drag and drop.
- Browse square previews in a three-column layout. Enabled mods have gold borders.
- Scan INI files for toggle keys.
- Organize utility, NPC and monster mods separately from character skins.
- Launch the SRMI profile through XXMI and check for updates.
- Switch between Korean and English using **KR / EN** in the title bar.

### Get started

1. Open the **[latest release](https://github.com/anjgkrhdlTwl/FictionArchive/releases/latest)** and download `FictionArchive-…-Windows-KR-EN.zip` from **Assets**. Do not use GitHub's **Source code (zip)** download.
2. Extract the entire ZIP and run `허구기록실.exe`. Keep the executable, `Assets` and `UpdateHelper.exe` together.
3. Select your XXMI installation, or manually choose `XXMI Launcher.exe` and `SRMI\Mods` in Settings.
4. Select a character, choose **Add Mods**, and import a folder or ZIP.
5. Enable the mod you want to use, then choose **Launch Mods**.

The game and XXMI / SRMI must be installed separately. You do not need to download `update.json` manually.

### How mod states work

Imported mods are copied into the connected `SRMI\Mods` folder and start disabled. Disabling adds `DISABLED_` to the folder name; enabling removes it. The files remain available. Delete sends the folder to the Recycle Bin after confirmation.

**Enabling a mod does not automatically disable another active mod.** A confirmation appears if another mod for the same character is already enabled. Disable the previous mod yourself if you only want one active. Restart the game after changes.

### Notes

Mod files, including Hide UID and No Transparency, are not bundled. Automatic extraction supports ZIP; extract RAR or 7z archives first. ShaderFixes-only files are not supported. Detected toggle keys may depend on conditions or external references. Keep the manager's `Data` folder when upgrading to preserve your settings and assignments.

See **`README.en.md`** inside the download for detailed instructions.

</details>

## 문제 제보 · Feedback

[Issues](https://github.com/anjgkrhdlTwl/FictionArchive/issues)에 사용한 버전, 문제가 발생한 상황, 재현 방법을 알려 주세요. 화면을 첨부하면 확인에 도움이 됩니다. 로그를 공유할 때는 개인 경로 등 공개하고 싶지 않은 정보를 지워 주세요.

Please include the application version, what happened, and steps to reproduce the issue. Screenshots are helpful. Remove private information before sharing logs.

## 개발자 후원 · Support

**[☕ 개발자에게 커피 한 잔 후원하기 · Buy Me a Coffee](https://buymeacoffee.com/wmjh5555)**

후원은 선택사항이며, 모든 기능은 후원 없이 사용할 수 있습니다.  
Donations are optional. All features are available without donating.

---

이 프로젝트는 비공식 도구이며 HoYoverse와 제휴하거나 공식 승인을 받은 프로그램이 아닙니다. 게임 이미지와 관련 자료의 권리는 각 권리자에게 있습니다.  
This is an unofficial project and is not affiliated with or endorsed by HoYoverse. Game artwork and related assets belong to their respective rights holders.

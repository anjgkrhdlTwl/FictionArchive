<div align="center">

<img src="docs/images/logo.png" width="112" alt="Fiction Archive logo">

# Fiction Archive

**Organize your Star Rail mods in one place.**

Windows 64-bit · XXMI / SRMI · English / 한국어

**[Download](https://github.com/anjgkrhdlTwl/FictionArchive/releases/latest)** &nbsp; | &nbsp; **[Report an Issue](https://github.com/anjgkrhdlTwl/FictionArchive/issues)** &nbsp; | &nbsp; **[☕ Support](https://buymeacoffee.com/wmjh5555)**

</div>

---

## About

Fiction Archive is an unofficial Honkai: Star Rail mod manager that manages mods in **your connected XXMI installation’s `SRMI\Mods` folder**. Organize mods by character, browse previews, and enable or disable the mods you want to use.

The app features a navy-and-gold theme and supports both English and Korean.

## Features

| Feature | Description |
| :--- | :--- |
| Character browsing | Browse by Element, Path, or Name |
| Trailblazer forms | Manage male and female Trailblazers separately, with mods organized by Path |
| Mod imports | Import folders and ZIP, RAR, or 7Z archives using a file picker or drag and drop |
| Previews | Square previews in a three-column layout, with gold borders for enabled mods |
| Image support | Automatically convert WebP images to PNG previews and resize large previews |
| Enable / disable | Switch mod states while keeping the files available |
| Toggle-key scanner | Find toggle keys in a mod’s INI files |
| Other mods | Separate categories for Hide UID, transparency fixes, NPCs, monsters, and other mods |
| GameBanana browser | Browse public listings with previews, authors, publication dates, views, and likes; search by character name, sort, and change pages |
| Sensitive previews | An option to show or hide sensitive previews in the GameBanana browser |
| FIX browser | Browse a curated list of fixes by game version, with search, previews, and links to original posts |
| Launch & updates | Launch SRMI through XXMI; check for app updates and show **NEW** when a newer stable release is detected |
| Language & settings | Switch languages with **KR / EN**; view the current app version in Settings |

## Download & Get Started

**Requirements:** 64-bit Windows, .NET Framework 4.8, and a separately installed copy of the game and XXMI / SRMI.

1. Open the **[latest release](https://github.com/anjgkrhdlTwl/FictionArchive/releases/latest)** and download `FictionArchive-v1.0.1-Windows-KR-EN.zip` from **Assets**, or the equivalent ZIP for a newer release. Do not download **Source code (zip)** to install the app.
2. Extract the **entire ZIP** into a folder and run `허구기록실.exe`. Keep all extracted files and folders together.
3. Select your XXMI installation from the search results. If you cancel the search or your installation is not found, select `XXMI Launcher.exe` and the `SRMI\Mods` folder in Settings.
4. Select a character and add a mod folder or a ZIP, RAR, or 7Z archive.
5. Enable the mod you want to use, then select **Launch Mods**.

Mod files are not included. Hide UID and transparency-fix mods must also be added separately.

### Updating

Use the **Update** button to check for a newer release. You can also download the release ZIP and apply it through the update ZIP option in Settings.

Keep the manager’s **`Data` folder** when moving to a new installation; it contains your settings and character assignments. You do not need to download `update.json` manually—it is used by the updater.

## How Are Mods Managed?

Imported mods are copied into the connected **`SRMI\Mods` folder** and start disabled. Your original source files are preserved.

- **Enable:** Removes the `DISABLED_` prefix from the mod folder’s name.
- **Disable:** Adds `DISABLED_` to the folder’s name. The files remain in place.
- **Delete:** Sends the managed mod folder to the Windows Recycle Bin after confirmation.

**Enabling one mod does not automatically disable another.** If a mod for the same character is already enabled, a confirmation appears. Disable the previous mod yourself if you only want one active. Restart the game to apply changes.

## GameBanana & FIX Browsing

The **GB** button opens the GameBanana browser. Character selections search listings by name, so results may include related posts. Public NSFW listings are included, and sensitive previews can be shown or hidden. Restricted or login-only content is not unlocked by the app.

The **FIX** browser displays a curated catalog with newer game versions first. Refreshing checks for catalog changes; it does not automatically discover every new fix on GameBanana. Both browsers link to original posts. They do not automatically run fix tools or apply patches to your mods.

## Notes

- Other-mod categories manage INI-based mods intended for the Mods folder. ShaderFixes-only files are not supported.
- Toggle-key scanning reads keys from INI files. Actual behavior can depend on conditions or external references.
- WebP previews are converted based on the image’s actual format. Renaming a file extension alone does not convert an image.
- Online browsing and update checks require an internet connection.

See **`README.en.md`** inside the downloaded ZIP for more detailed instructions.

## Feedback

Report problems through **[Issues](https://github.com/anjgkrhdlTwl/FictionArchive/issues)**. Include the app version, what happened, and steps to reproduce it. Screenshots are helpful. Remove private information, such as personal file paths, before sharing logs.

## Support

**[☕ Buy the developer a coffee](https://buymeacoffee.com/wmjh5555)**

Donations are optional. All features are available without donating.

---

<details>
<summary><strong>한국어 안내 — 클릭하여 펼치기</strong></summary>

## 허구기록실 소개

허구기록실은 **연결한 XXMI의 `SRMI\Mods` 폴더에 있는 모드를 관리하는 비공식 스타레일 모드 매니저**입니다. 캐릭터별로 모드를 정리하고, 미리보기를 보면서 원하는 모드를 켜거나 끌 수 있습니다.

남청색과 금빛 테마를 사용하며, 한국어와 영어를 지원합니다.

### 주요 기능

| 기능 | 설명 |
| :--- | :--- |
| 캐릭터 분류 | 속성·운명의 길·이름으로 탐색 |
| 개척자 관리 | 남자·여자 개척자를 나누고 각 운명의 길별로 모드 관리 |
| 간편한 추가 | 폴더·ZIP·RAR·7Z 선택 또는 드래그 앤 드롭으로 추가 |
| 미리보기 | 정사각형 이미지와 가로 3열 카드, 활성화된 모드는 금빛 테두리로 표시 |
| 이미지 지원 | WebP 이미지를 PNG 미리보기로 자동 변환하고 큰 이미지 크기 최적화 |
| 모드 켜기·끄기 | 파일을 보관한 채 활성화·비활성화 전환 |
| 토글키 확인 | 모드의 INI 파일에서 토글키를 찾아 표시 |
| 기타 모드 | UID 숨김·투명 방지·NPC·몬스터 등 별도 분류 |
| GameBanana 탐색 | 미리보기·작성자·게시 날짜·조회수·좋아요 표시, 캐릭터 이름 검색·정렬·페이지 이동 |
| 민감한 미리보기 | GameBanana의 민감한 미리보기 표시·숨김 선택 |
| FIX 탐색 | 게임 버전별로 정리한 목록, 검색·미리보기·원본 게시글 연결 |
| 실행·업데이트 | XXMI를 통한 SRMI 실행, 새 정식 업데이트 확인 시 **NEW** 표시 |
| 언어·설정 | 상단 **KR / EN**으로 언어 전환, 설정창에서 현재 버전 확인 |

### 다운로드 및 시작하기

**필요 환경:** Windows 64비트, .NET Framework 4.8. 게임과 XXMI / SRMI는 별도로 설치해야 합니다.

1. **[최신 릴리스](https://github.com/anjgkrhdlTwl/FictionArchive/releases/latest)**의 **Assets**에서 `FictionArchive-v1.0.1-Windows-KR-EN.zip` 또는 이후 버전의 배포용 ZIP을 다운로드하세요. 설치할 때는 **Source code (zip)**을 받지 마세요.
2. **ZIP 전체를 압축 해제**하고 `허구기록실.exe`를 실행하세요. 압축 해제한 파일과 폴더는 함께 보관하세요.
3. XXMI 검색 결과에서 사용할 설치를 선택하세요. 검색을 취소했거나 설치를 찾지 못했다면 설정에서 `XXMI Launcher.exe`와 `SRMI\Mods` 경로를 직접 선택하세요.
4. 캐릭터를 선택하고 모드 폴더나 ZIP·RAR·7Z 압축파일을 추가하세요.
5. 사용할 모드의 **적용하기**를 누르고 **모드 실행**으로 시작하세요.

모드 파일은 포함되어 있지 않습니다. UID 숨김·투명 방지 모드도 해당 파일을 별도로 추가해야 합니다.

### 업데이트

상단 **업데이트** 버튼으로 새 버전을 확인할 수 있습니다. 배포용 ZIP을 직접 다운로드한 뒤 설정의 **업데이트 ZIP 직접 적용**에서 선택해도 됩니다.

새 폴더로 옮길 때는 설정과 캐릭터 지정 정보가 담긴 **`Data` 폴더**를 보관하세요. `update.json`은 프로그램이 업데이트를 확인할 때 사용하는 파일이므로 직접 받을 필요가 없습니다.

### 모드는 어떻게 관리되나요?

새로 추가한 모드는 원본을 복사해 연결된 **`SRMI\Mods` 폴더**로 가져오며, 처음에는 비활성화됩니다. 원본 파일은 그대로 보존됩니다.

- **적용하기:** 모드 폴더 이름의 `DISABLED_` 접두사를 제거합니다.
- **해제하기:** 폴더 이름 앞에 `DISABLED_`를 붙입니다. 파일은 그대로 남습니다.
- **삭제:** 확인 후 관리 중인 모드 폴더를 Windows 휴지통으로 보냅니다.

**다른 모드를 켜도 이미 켜진 모드가 자동으로 꺼지지는 않습니다.** 같은 캐릭터의 모드를 추가로 켜려 하면 확인창이 표시됩니다. 하나만 사용할 때는 기존 모드를 해제한 뒤 원하는 모드를 적용하세요. 변경 사항은 게임을 다시 실행해 반영하세요.

### GameBanana 및 FIX 탐색

상단 **GB** 버튼으로 GameBanana 탐색 창을 열 수 있습니다. 캐릭터 선택은 이름 검색을 이용하므로 관련 게시글도 함께 나올 수 있습니다. 공개 NSFW 게시물도 목록에 포함되며, 민감한 미리보기는 표시하거나 숨길 수 있습니다. 접근이 제한되거나 로그인이 필요한 게시물을 우회해서 보여주지는 않습니다.

**FIX** 탐색은 등록된 목록을 최신 게임 버전 순으로 보여줍니다. 새로고침하면 목록의 변경 사항을 확인하지만, GameBanana의 모든 새 FIX를 자동으로 찾아 등록하는 방식은 아닙니다. 두 탐색 창 모두 원본 게시글로 연결하며, FIX 도구를 자동 실행하거나 모드에 패치를 적용하지 않습니다.

### 알아두세요

- 기타 모드 분류는 Mods 폴더용 INI 모드를 관리합니다. ShaderFixes 전용 파일은 지원하지 않습니다.
- 토글키 스캔은 INI에 기록된 키를 보여줍니다. 조건이나 외부 참조에 따라 실제 동작은 달라질 수 있습니다.
- WebP 미리보기는 실제 이미지 형식을 확인해 변환합니다. 확장자 이름만 바꾸는 것은 이미지 변환이 아닙니다.
- 온라인 탐색과 업데이트 확인에는 인터넷 연결이 필요합니다.

자세한 사용법은 다운로드한 ZIP 안의 **`README.ko.md`**를 참고하세요.

### 문제 제보

**[Issues](https://github.com/anjgkrhdlTwl/FictionArchive/issues)**에 앱 버전, 문제가 발생한 상황, 재현 방법을 알려 주세요. 화면을 첨부하면 확인에 도움이 됩니다. 로그를 공유할 때는 개인 경로 등 공개하고 싶지 않은 정보를 지워 주세요.

### 개발자 후원

**[☕ 개발자에게 커피 한 잔 후원하기](https://buymeacoffee.com/wmjh5555)**

후원은 선택사항이며, 모든 기능은 후원 없이 사용할 수 있습니다.

이 프로젝트는 비공식 도구이며 HoYoverse와 제휴하거나 공식 승인을 받은 프로그램이 아닙니다. 게임 이미지와 관련 자료의 권리는 각 권리자에게 있습니다.

</details>

---

This is an unofficial project and is not affiliated with or endorsed by HoYoverse. Game artwork and related assets belong to their respective rights holders.

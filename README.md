# cwDuXplorer (듀스플로러)

![cwDuXplorer Logo](files/duXplorer.png) <!-- 로고 이미지 추가 시 경로 지정 -->

**cwDuXplorer**는 윈도우 탐색기의 친숙함을 유지하면서 듀얼 패널로 파일 관리를 간편하게 할 수 있는 파일 탐색기입니다. 개인적인 필요로 개발된 간단한 도구로, 파일 작업의 효율성을 높여줍니다.

---

## 소개 (Introduction)

### 한국어

**cwDuXplorer (듀스플로러) - 내가 원하던 듀얼 패널 파일 탐색기**

윈도우 탐색기를 쓰다 보면 불편한 순간이 있습니다. 파일을 복사하거나 이동할 때 두 작업 공간을 한 번에 볼 수 없어 창을 계속 전환해야 하고, Microsoft 공식 가이드대로 Snap Assist로 탐색기를 나란히 띄워보려 해도 매번 창 크기를 조정하는 것도 꽤 번거롭습니다. 창 크기를 맞췄더라도 여러 창을 띄워 사용하다 보면 작업하던 창이 뒤섞이거나 가려지기 일쑤라 효율이 떨어집니다.

그래서 예전부터 서드파티 파일 탐색기를 여러 개 사용해봤지만 저에게 딱 맞는 프로그램을 찾기가 어려웠습니다. 너무 복잡하거나 윈도우 탐색기와 달라 적응하기 어려웠습니다. 제가 원했던 것은 윈도우 탐색기의 친숙함을 유지하면서 듀얼 패널로 간편히 파일을 관리할 수 있는 도구였습니다. 복잡한 기능은 원하지 않았기에 Microsoft에서 윈도우 탐색기를 듀얼 패널로 만들어주면 좋겠지만, 그럴 가능성은 없어 보였습니다. 그래서 직접 개발해보기로 했습니다.

그 결과물이 바로 cwDuXplorer(듀스플로러)입니다. 이름처럼 듀얼 패널로 설계되어 파일을 이동하거나 비교할 때 두 공간을 동시에 볼 수 있고, 윈도우 탐색기의 인터페이스를 기반으로 누구나 쉽게 적응할 수 있도록 했습니다. 개인적인 필요로 만든 프로그램이라 화려하지 않지만, 실제로 사용해보니 파일 작업이 훨씬 수월해졌습니다. 비슷한 불편함을 느끼셨다면 한 번 사용해보시겠습니까? 윈도우 탐색기의 한계가 아쉬웠던 분들에게 도움이 될 거라 생각합니다.

관심이 있다면 cwDuXplorer(듀스플로러)를 다운로드해 사용해보세요. 파일 관리가 더 효율적으로 변하는 경험을 느껴보실 수 있습니다. 사용 후 피드백도 환영합니다!

### English

**cwDuXplorer - The Dual-Panel File Explorer I Always Wanted**

Using Windows Explorer often comes with inconveniences. When copying or moving files, you can’t view both workspaces at once, forcing constant window switching. Microsoft’s official guide recommends using Snap Assist to align Explorer windows side by side, but resizing them every time is quite tedious. Even when aligned, multiple open windows tend to get mixed up or obscured, hampering efficiency.

I explored various third-party file explorers, but finding one that suited me was challenging. They were either overly complex or too different from Windows Explorer to feel intuitive. What I wanted was a tool that retained Windows Explorer’s familiarity while offering a dual-panel interface for seamless file management. I didn’t need elaborate features—just a simple solution, perhaps like Microsoft combining two Explorer windows. Since that seemed unlikely, I decided to build it myself.

The result is **cwDuXplorer**. Designed with a dual-panel layout, it allows you to view and compare two folders simultaneously, making file transfers and comparisons effortless. Based on Windows Explorer’s interface, it’s easy for anyone to adapt to. Built out of personal need, it’s not flashy, but using it has significantly streamlined my file tasks. If you’ve felt frustrated by Windows Explorer’s limitations, would you consider giving it a try? I believe it could be helpful.

Interested? Download **cwDuXplorer** and experience more efficient file management. Feedback is always welcome!

---

## 설치 (Installation)

1. [릴리스 페이지](https://github.com/ImWanderMaker/cwDuxplorer/releases)에서 최신 버전을 다운로드하세요.
2. 다운로드한 실행 파일(`cwDuXplorer.exe`)을 실행하여 설치 없이 바로 사용 가능합니다.

> **참고**: Windows 10 이상에서 최적화되어 있습니다.

---

## 사용법 (Usage)

### 한국어

**cwDuXplorer**는 윈도우 탐색기와 유사한 인터페이스로 기본적인 파일 작업(복사, 이동, 삭제 등)을 동일하게 지원합니다. 추가로, 듀얼 패널과 바로가기 기능을 통해 더 효율적인 파일 관리를 제공합니다.

- **듀얼 패널**:
  - 왼쪽과 오른쪽 패널에서 각각 다른 폴더를 열어 파일을 비교하거나 이동하세요.
  - 드래그 앤 드롭으로 파일을 간편히 복사하거나 이동할 수 있습니다.

- **바로가기 기능**:
  - **바로가기 툴바**: 프로그램 상단에 위치한 툴바로, 자주 사용하는 경로를 즐겨찾기 형태로 등록해 빠르게 이동할 수 있습니다. 툴바는 드래그로 좌측, 우측, 하단, 상단으로 위치를 조정 가능합니다.
  - **바로가기 버튼**: 왼쪽 클릭 시 왼쪽 패널에 해당 경로가 열리고, 오른쪽 클릭 시 오른쪽 패널에 열립니다.
  - **바로가기 관리**:
    - **등록**: 툴바의 가장 왼쪽에 있는 관리 버튼을 클릭하세요. 왼쪽 클릭은 왼쪽 패널의 현재 경로를, 오른쪽 클릭은 오른쪽 패널의 현재 경로를 바로가기로 등록합니다.
    - **수정/삭제**: 바로가기 버튼을 `Ctrl` 키를 누른 상태로 클릭(왼쪽 또는 오른쪽)하면 컨텍스트 메뉴가 나타납니다. 여기서:
      - **수정**: 버튼의 이름과 경로를 편집할 수 있는 창이 열립니다. 수정 후 저장하면 툴바에 반영됩니다.
      - **삭제**: 선택한 바로가기를 제거합니다.
      - **경로 복사**: 바로가기의 경로를 클립보드에 복사합니다.
    - **순서 변경**: 관리 버튼을 `Ctrl` 키와 함께 클릭하면 바로가기 버튼의 순서를 조정할 수 있습니다.

자세한 사용법은 [여기](path/to/documentation)에서 확인하세요.

### English

**cwDuXplorer** offers an interface similar to Windows Explorer, supporting standard file operations (copy, move, delete, etc.) with the same ease. Additionally, its dual-panel layout and shortcut feature enhance file management efficiency.

- **Dual Panels**:
  - Open different folders in the left and right panels to compare or transfer files.
  - Drag and drop files for quick copying or moving.

- **Shortcut Feature**:
  - **Shortcut Toolbar**: Located at the top by default, this toolbar lets you bookmark frequently used paths for quick access. You can drag it to the left, right, bottom, or top of the window.
  - **Shortcut Buttons**: Left-click a button to open its path in the left panel; right-click to open it in the right panel.
  - **Shortcut Management**:
    - **Add**: Click the management button (leftmost on the toolbar). A left-click adds the current left panel’s path as a shortcut; a right-click adds the right panel’s path.
    - **Edit/Delete**: Hold `Ctrl` and click (left or right) a shortcut button to open a context menu, where you can:
      - **Edit**: Open a dialog to modify the button’s name and path. Save to update the toolbar.
      - **Delete**: Remove the selected shortcut.
      - **Copy Path**: Copy the shortcut’s path to the clipboard.
    - **Reorder**: Hold `Ctrl` and click the management button to rearrange the shortcut buttons.

For detailed instructions, see [here](path/to/documentation).

---

## 기여 (Contributing)

버그 리포트, 기능 제안, 코드 기여를 환영합니다!  
1. 이슈를 등록하거나 풀 리퀘스트를 보내주세요.
2. [기여 가이드라인](path/to/CONTRIBUTING.md)을 참고하세요.

---

## 라이선스 (License)

이 프로젝트는 [MIT License](LICENSE) 하에 배포됩니다.

---

## 연락처 (Contact)

질문이나 피드백이 있다면 [이메일](mailto:ocean99blue@gmail.com) 또는 [이슈 트래커](https://github.com/ImWanderMaker/cwDuxplorer/issues)로 연락 주세요.

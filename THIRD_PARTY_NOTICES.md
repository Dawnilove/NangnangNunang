# 오픈소스 고지 (Third-Party Notices)

**바탕화면 고양이 1.2.0** 배포판에는 아래 오픈소스 구성 요소가 들어 있어요.
각 구성 요소는 자기 라이선스를 따르고, 바탕화면 고양이의 [LICENSE](LICENSE)는 그 권리를 줄이거나 바꾸지 않아요.
라이선스 전문은 `licenses/` 폴더(프로그램 안에서는 **설정 → 라이선스**)에 있어요.

| 구성 요소 | 버전 | 라이선스 | 홈페이지 | 전문 |
|---|---|---|---|---|
| Python | 3.14.7 | PSF-2.0 | https://www.python.org | `licenses/Python-3.14.7/` |
| PyInstaller 부트로더 |  | GPL-2.0-or-later + 배포 예외(만든 프로그램은 자유롭게 배포 가능) | https://pyinstaller.org |  |
| annotated-types | 0.8.0 | MIT | https://github.com/annotated-types/annotated-types | `licenses/annotated-types-0.8.0/` |
| anthropic | 1.11.0 | MIT License | https://github.com/anthropics/anthropic-sdk-python | `licenses/anthropic-1.11.0/` |
| anyio | 4.15.1 | MIT |  | `licenses/anyio-4.15.1/` |
| docstring_parser | 0.18.0 | MIT License | https://github.com/rr-/docstring_parser | `licenses/docstring_parser-0.18.0/` |
| h11 | 0.16.0 | MIT License | https://github.com/python-hyper/h11 | `licenses/h11-0.16.0/` |
| httpcore2 | 2.13.1 | BSD-3-Clause | https://github.com/pydantic/httpx2 | `licenses/httpcore2-2.13.1/` |
| httpx2 | 2.13.1 | BSD-3-Clause | https://github.com/pydantic/httpx2 | `licenses/httpx2-2.13.1/` |
| idna | 3.20 | BSD-3-Clause | https://github.com/kjd/idna | `licenses/idna-3.20/` |
| jiter | 0.17.0 | MIT | https://github.com/pydantic/jiter/ | `licenses/jiter-0.17.0/` |
| pydantic | 2.13.5 | MIT | https://github.com/pydantic/pydantic | `licenses/pydantic-2.13.5/` |
| pydantic_core | 2.46.5 | MIT | https://github.com/pydantic | `licenses/pydantic_core-2.46.5/` |
| PySide6_Essentials | 6.11.2 | LGPL-3.0-only (Qt for Python 오픈소스 라이선스 중 LGPL을 따라 사용) | https://pyside.org | `licenses/PySide6_Essentials-6.11.2/` |
| shiboken6 | 6.11.2 | LGPL-3.0-only (Qt for Python 오픈소스 라이선스 중 LGPL을 따라 사용) | https://pyside.org | `licenses/shiboken6-6.11.2/` |
| sniffio | 1.3.1 | MIT License, Apache Software License | https://github.com/python-trio/sniffio | `licenses/sniffio-1.3.1/` |
| truststore | 0.10.4 | MIT | https://github.com/sethmlarson/truststore | `licenses/truststore-0.10.4/` |
| typing-inspection | 0.4.4 | MIT | https://github.com/pydantic/typing-inspection | `licenses/typing-inspection-0.4.4/` |
| typing_extensions | 4.16.0 | PSF-2.0 | https://github.com/python/typing_extensions | `licenses/typing_extensions-4.16.0/` |

## Qt for Python (PySide6) · Qt 6 — GNU LGPL 3.0

- 이 프로그램은 Qt for Python(PySide6, shiboken6)과 Qt 6 라이브러리를 **GNU Lesser General Public License 3.0**에 따라 **수정하지 않고** 사용해요.
- Qt와 PySide6의 소스 코드는 https://code.qt.io/cgit/pyside/pyside-setup.git/ 와 https://download.qt.io/official_releases/QtForPython/ 에서 받을 수 있어요.
- **라이브러리 바꿔 끼우기**: 압축 파일 배포판(`DesktopCat-<버전>-win-x64.zip`)은 Qt·PySide6 파일이 `DesktopCat/_internal/PySide6/`에 따로 들어 있어서, 같은 버전대의 다른 빌드로 바꿔 끼워 실행할 수 있어요.
  실행 파일 하나짜리 배포판(Portable)은 실행할 때 같은 파일을 임시 폴더에 풀어 쓰며, 바꿔 끼우려면 압축 파일 배포판을 쓰세요.
- LGPL 3.0 전문과, LGPL 3.0이 참조하는 GPL 3.0 전문은 `licenses/PySide6_Essentials-*/` 폴더에 있어요.
- Qt 자체에 들어 있는 제3자 구성 요소(예: zlib, libpng, FreeType, HarfBuzz, PCRE2 등)의 라이선스는 https://doc.qt.io/qt-6/licenses-used-in-qt.html 에 정리돼 있어요.

## 상표

"Claude"와 "Anthropic"은 Anthropic PBC의 상표예요. "Qt"는 The Qt Company Ltd.의 상표예요. "Python"은 Python Software Foundation의 상표예요.
이 프로그램은 이 회사·재단들과 관계가 없고, 이들이 후원하거나 보증하지 않아요.

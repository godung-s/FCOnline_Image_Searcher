FC 온라인 선수 이미지 검색기 (FCOnline Image Searcher)
NEXON Open API를 활용하여 FC 온라인 (구 FIFA 온라인 4) 선수들의 고해상도 액션 이미지를 검색하고 다운로드할 수 있는 Python GUI 애플리케이션입니다.

주요 기능
선수 이름 또는 ID로 검색:
선수 이름(예: "손흥민") 또는 고유 ID(예: "10000001")로 해당 선수의 모든 시즌 이미지를 한 번에 검색합니다.
이름 자동 완성 기능을 지원하여 선수를 쉽게 찾을 수 있습니다.

시즌 코드로 검색:
시즌 ID(예: 255)를 입력하여 해당 시즌에 포함된 모든 선수의 이미지를 검색합니다.
공식 메타데이터(seasonid.json)에 아직 등재되지 않은 신규 시즌(미확인 시즌)도 탐색할 수 있습니다.

간편한 저장:
검색된 이미지 위에서 마우스 오른쪽 버튼을 클릭하면 원하는 위치에 바로 .png 파일로 저장할 수 있습니다.

자동 메타데이터 관리:
프로그램 실행 시 최신 spid.json (선수 목록) 및 seasonid.json (시즌 목록) 파일을 자동으로 확인하고 다운로드합니다.
다운로드한 데이터는 사용자의 %APPDATA%\FCOnlineImageSearcher 폴더에 저장되어 매번 다운로드할 필요 없이 빠르게 로드됩니다.

중요: 사용 시 주의사항
한국 서버 전용: 이 프로그램은 NEXON의 FC 온라인 한국 서비스 API를 기반으로 제작되었습니다.
다른 국가(예: 베트남, 태국, 중국 등)의 FC 온라인 서버에서는 선수 ID나 이미지 경로가 호환되지 않아 작동하지 않습니다.

언어: Python 3.11

GUI: Tkinter (파이썬 기본 라이브러리)

라이브러리: requests (API 통신), Pillow (PIL) (이미지 처리)

FC Online Image Searcher
A Python GUI application built with Tkinter that utilizes the NEXON Open API to search for and download high-resolution action images (minifaces) of FC Online (formerly FIFA Online 4) players.

Key Features
Search by Player Name or ID:
Searches for all available seasons of a specific player using their name (e.g., "Son Heung-Min") or unique player ID (e.g., "10000001").
Includes an autocomplete feature in the search box for easy player lookup.

Search by Season Code:
Input a 3-digit season ID (e.g., 255) to find all players associated with that specific season.
Supports a "discovery mode" to find players from new or unlisted seasons not yet present in the official seasonid.json.

Easy Image Saving:
Right-click on any image in the results grid to save it directly to your computer as a .png file.

Automatic Metadata Management:
Automatically checks for and downloads the latest spid.json (player list) and seasonid.json (season list) files on launch.
This data is stored locally in the user's %APPDATA%\FCOnlineImageSearcher folder for faster loading times.

Important Usage Note
Korea Server Only: This tool is specifically built for the Korean FC Online service provided by NEXON.
It is not compatible with other regional servers (e.g., Vietnam, Thailand, China) as the player IDs and image CDN paths differ.

Language: Python 3.11

GUI: Tkinter (Python's native GUI library)

Libraries: requests (for API communication), Pillow (PIL) (for image processing)

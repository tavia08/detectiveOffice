역사탐정사무소 최종 통합본 - 10초 읽기 / index 오류 수정본

중요
- 이전 통합본에서 index.html의 </body> 문자열 치환이 잘못되어 JavaScript 코드가 화면에 노출되는 문제가 있었습니다.
- 이 버전은 그 오류를 수정했습니다.
- 통합 코드는 실제 문서 끝에 1회만 삽입됩니다.
- 대표 사료수사 31개는 자료 전체 읽기 시간을 10초로 유지합니다.

GitHub 적용
1. 현재 저장소의 index.html을 이 파일의 index.html로 교체
2. source_data 폴더를 이 버전으로 통째로 교체
3. case_data / stamps / assets는 그대로 유지
4. Commit → Push
5. GitHub Pages 반영 후 Ctrl+F5

정상 확인
- 첫 화면에 JavaScript 코드가 글자로 노출되지 않아야 함
- 1~5단원 대표 사료수사가 정상 표시되어야 함
- 대표 사료수사 진입 후 10초 뒤 '정체 확인' 버튼이 활성화되어야 함

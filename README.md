# know-how
개발 참고 사항들

## open-api generator에서 spring boot model 생성 안되는 문제
* @PutMapping(value = "/company/{id}", consumes = {MediaType.APPLICATION_JSON_VALUE, MediaType.MULTIPART_FORM_DATA_VALUE}) 
  2가지 형태로 보냈을 때, consumes에서 모두 선언해줘야 관련된 Dto가 정상적으로 model로 생성됨

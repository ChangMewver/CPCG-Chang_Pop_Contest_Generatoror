사용법

1. CSV 파일
CSV 파일을 엑셀로 열어, 곡에 대한 정보를 기입하세요.
단, 참가번호는 수정하지 말아주세요. 스크립트에서 인식하기 위해 필요합니다.
CSV 파일의 구조 상, 큰따옴표( " )는 파싱하지 못하고, 프로그램이 굳어버립니다.
유니티 폰트 에셋의 구조 상, 일부 특수문자나 외국어는 인식이 불가합니다.

2. Com_Images
곡의 썸네일이나 복면 등, 이미지를 넣을 수 있습니다.
CSV파일의 '이미지 이름'에 기입한 파일을 불러옵니다.
파일명의 기본형은 image+숫자 입니다. (image1, image2 등)
파일명을 인식하지 못하였을 경우, 표시하지 않습니다.
png만 지원합니다.

3. Com_Videos
재생할 영상을 넣을 수 있습니다.
CSV파일의 '영상 이름'에 기입한 파일을 불러옵니다.
기본형은 video+숫자 입니다. (video1, video2 등)
파일명을 인식하지 못하였을 경우, 프로그램이 굳어버립니다.
mp4만 지원합니다.
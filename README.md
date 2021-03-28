# API
## A. Fshare API: [apis.delnegend.com/fshare](https://apis.delnegend.com/fshare)
- Param:
  - url: link thư mục hoặc file fshare
  - fastid *(optional)*: để true nếu chỉ cần lấy ID
- Kiểu dữ liệu trả về: json
- Demo
  1. Trường hợp link hợp lệ
    
      ![demo](screenshots/fshareAPI/valid.file.png)

      ![demo](screenshots/fshareAPI/valid.folder.png)

  2. Trường hợp link không hợp lệ

      ![unvalid](screenshots/fshareAPI/unvalid.png)

<hr>

## B. SRI Generator
- Param
  - url: link file css/js cần generate hash<br>
  - sha *(optional)*: 256, 384 hoặc 512 tuỳ nhu cầu
- Kiểu dữ liệu trả về: json
- Demo

  1. Trường hợp chỉ có url

      ![urlOnly](screenshots/srigenAPI/urlOnly.png)

  2. Trường hợp có param "sha"

      ![withSHA256](screenshots/srigenAPI/withParam256.png)

      ![withSHA384](screenshots/srigenAPI/withParam384.png)

      ![withSHA512](screenshots/srigenAPI/withParam512.png)
      
      <hr>

## C. Movie ratings:
### IMDB: [apis.delnegend.com/imdb](https://apis.delnegend.com/imdb)
- Param: id (string), raw (boolean)
### RottenTomatoes: [apis.delnegend.com/rottentomatoes](https://apis.delnegend.com/rottentomatoes)
- Param: url (string), raw (boolean)

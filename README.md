# Artpia
Artpia ERC721 Contract 


위 컨트랙트는 아스타 메인넷에 배포 되었습니다.

Contract Address:0x42195c8857Edbd1e671Cb1AFA63C04805ec66098


런치패드 민팅 시 소요되는 ASTR 개수를 조정하고 싶다면 아래 코드의 "1000"을 수정하면 됩니다.

https://github.com/WepleProject/Artpia/blob/main/Artpia-Contract/contracts/Artpia.sol#L26


그리고 해당 컨트랙트의 TokenURI는 표준을 따릅니다.

BaseURI가 http://baseURI.xyz/ 일경우

TokenURI는 http://baseURI.xyz/{tokenID} 입니다.

https://github.com/OpenZeppelin/openzeppelin-contracts/blob/v5.0.0-rc.0/contracts/token/ERC721/ERC721.sol#L92

위 오픈제플린을 보면 "/" 구분자를 BaseURI와 TokenID 사이에 넣어주지 않으니

꼭 BaseURI를 설정할 때 주소가 http://baseURI.xyz이라면 http://baseURI.xyz/ 으로 설정해줘야 합니다.


 

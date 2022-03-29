# ChannelTalk Bug example

## How to Reproduce

clone the repo

`.env.local`에 채널톡 플러그인 키를 넣어주시고

빌드를 진행합니다. (개발환경에서는 버그가 발생하지 않습니다)

채널톡 스크립트는 `_app.js` 에서 삽입합니다!

```sh
yarn install
yarn build
yarn start
```

이후 채널톡 버튼을 킨 다음 다른 페이지로 이동하는 버튼을 클릭하면 스타일이 깨지는걸 확인하실 수 있습니다.

해당 레포는 [이 예시를 기반으로 제작되었습니다](https://github.com/mui/material-ui/tree/master/examples/nextjs)

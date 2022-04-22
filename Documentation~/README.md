# DroneMovement on VRC
"DroneMovement on VRC" はVRC専用のドローン用ギミックです。
制作者は[FORNO](https://twitter.com/forno_fornya)です。
ライセンスはMITライセンスとなっています。

## インストール
### 依存
[VRChat Avatars SDK3](https://vrchat.com/home/download)

### 手順
- Unityプロジェクトにある `Packages/manifest.json` を編集します。
- 以下の行を `dependencies` に追加します。

```json
"link.xmaho.movement.vrc.drone": "https://github.com/forno/DroneMovementOnVRC.git"
```

## Prefabs
- DroneMovementForQuest
- DroneMovementForBasic

### DroneMovementForQuest
*Quest*でも動作する追従ドローンギミックです。

`PhysBones`のみで構成されています。ボーン数は2です。

#### Note
*Quest*では`PhysBones`の数に制限がありますので、アバターの制限を超過しないようご注意ください。
もちろん*PC*でもご利用いただけます。

### DroneMovementForBasic
`Contraint`を用いて追従に加えて自然な向きの変更を行うドローンギミックです。

`PhysBones`と`LookAtConstraint`で構成されています。ボーン数は2です。

## LICENSE
This software is released under the MIT License, see LICENSE.md.
# acrylic-assets

亚克力价目表图片资源（临时 CDN，后续迁移至微信小程序云存储）。

## 目录结构

```
special/                       特殊材料
  mica/                        云母板
    cloud/                     云纹
    polarized-metallic/        偏光/金属色
    animal-pattern/            动物花纹
    translucent/               半透
    marble/                    大理石花纹
    fabric/                    布纹
    galaxy/                    星河系列
    shell/                     贝壳纹
  colored-acrylic/             有色亚克力
    luminous/                  夜光板
    solid/                     实色板
    frosted/                   磨砂板
    transparent/               透色板
  textured-acrylic/            纹理亚克力
    stripe/                    条纹
    water-ripple/              水波纹
  glitter-acrylic/             闪粉亚克力
    polka-dot-stripe/          波点彩条
    gold-silver-fleck/         洒金/洒银
    full-glitter/              满色闪粉
    fine-thread/               细螺纹
    glitter-transparent/       闪粉/透色

normal/                        普通板材
  transparent-charm/           透明挂件（挂件）
    clear/                     透明板
    laser/                     镭射板
    stained-glass/             彩窗工艺
    rainbow/                   彩虹板
    mirror/                    镜面板
  standee/                     亚克力立牌（立牌）
    clear/                     透明立牌
    multi-insert/              多插立牌
  shaker/                      亚克力摇摇乐（摇摇乐）
    standard/                  普通摇摇乐
    claw-machine/              娃娃机摇摇乐
    spring/                    弹簧摇摇乐
  clip/                        亚克力夹子（夹子）
    standard/                  普通夹子
  badge/                       亚克力徽章（徽章）
    standard/                  普通徽章
  color-paper/                 亚克力色纸（色纸）
    standard/                  普通色纸
  flip-open/                   亚克力开开乐（开开乐）
    standard/                  开开乐
  mahjong/                     亚克力麻将（麻将）
    standard/                  普通麻将
    depth/                     景深麻将
    quicksand/                 流沙麻将
  special-acrylic/             特殊亚克力
    carousel/                  旋转木马
    slide/                     滑滑梯
    pirate-ship/               海盗船
    seesaw/                    跷跷板
    spinning-standee/          旋转立牌
    magnetic-standee/          磁铁开关立牌
    card-insert-standee/       插卡立牌
    skateboard-standee/        滑板立牌
```

每个小类目录内按序号命名图片（`1.png`、`2.png` ...），`normal/` 下各小类一般只有 `1.png`。

## 引用方式（jsDelivr）

```
https://cdn.jsdelivr.net/gh/SaltApocalypse/acrylic-assets@<版本>/special/mica/cloud/1.png
https://cdn.jsdelivr.net/gh/SaltApocalypse/acrylic-assets@<版本>/normal/standee/clear/1.png
```

## 发布 / 更新

发布新图片后打 tag（如 `v1.0.2`）并创建 Release，然后更新小程序中的版本常量即可。

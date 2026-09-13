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
```

每个小类目录内按序号命名图片（`1.png`、`2.png` ...）。

## 引用方式（jsDelivr）

```
https://cdn.jsdelivr.net/gh/SaltApocalypse/acrylic-assets@<版本>/special/mica/cloud/1.png
```

发布新图片后打 tag（如 `v1.0.1`）并更新小程序中的版本常量即可。

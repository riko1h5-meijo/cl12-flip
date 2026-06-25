# タイトル行

1. 概要
説明文説明文説明文説明文説明文説明文

2. ソースコード
```python
from PIL import Image
import sys

# コメント行
input_image = sys.argv[1]
output_image = sys.argv[2]

img = Image.open(input_image)

img_flip = img.transpose(Image.FLIP_LEFT_RIGHT)

img_flip.save(output_image)
```
3. 使い方
3.1. 実行例
3,2. 出力結果

![AAA](./input.jpg)

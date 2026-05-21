# Chinese-ID-Calculator
[中] 基于 Scratch 的中国身份证第18位校验码计算器 | [EN] China ID Card 18th Digit Checksum Calculator built with Scratch.

🇨🇳 简体中文

🚀 项目简介
这是一个使用 Scratch 图形化编程实现的中国第二代身份证第 18 位校验码计算器。只要输入身份证的前 17 位数字，程序就会通过标准的 ISO 7064:1983.MOD 11-2 算法，精准计算出最后一位校验码（0-9 或 X）。

🎮 如何体验？
* 在线游玩： 👉 点击这里在 Scratch 官网查看作品 ( https://scratch.mit.edu/projects/1322840479 )
* 本地运行： 下载本仓库中的 .sb3 文件，然后导入到 Scratch 官网 ( https://scratch.mit.edu/ ) 或 Scratch 桌面版中。

🧮 算法原理
1. 加权求和： 将前 17 位数字分别乘以对应的权重系数（7, 9, 10, 5, 8, 4, 2, 1, 6, 3, 7, 9, 10, 5, 8, 4, 2）并相加得到总和。
2. 取模： 用总和除以 11 得到余数（0-10）。
3. 对应校验码： 根据余数对照表，换算出最终的第 18 位编码（1, 0, X, 9, 8, 7, 6, 5, 4, 3, 2）。

---

🇺🇸 English

🚀 About The Project
This is a Scratch-based calculator designed to compute the 18th digit (checksum) of the Chinese Resident Identity Card. By inputting the first 17 digits, the program applies the standard ISO 7064:1983.MOD 11-2 algorithm to accurately determine the final character (0-9 or X).

🎮 How to Play / Run?
* Play Online: 👉 Click here to view on Scratch Website ( https://scratch.mit.edu/projects/1322840479 )
* Run Locally: Download the .sb3 file from this repository and import it into Scratch Official Website ( https://scratch.mit.edu/ ) or Scratch Desktop.

🧮 How It Works
1. Weighted Sum: Multiply each of the first 17 digits by its corresponding weight coefficient (7, 9, 10, 5, 8, 4, 2, 1, 6, 3, 7, 9, 10, 5, 8, 4, 2) and sum them up.
2. Modulo Operation: Calculate the remainder by dividing the sum by 11.
3. Mapping: Map the remainder (0-10) to the final checksum character (1, 0, X, 9, 8, 7, 6, 5, 4, 3, 2).

---

📄 License
This project is licensed under the MIT License (LICENSE).

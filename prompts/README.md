# 中英文提示词

当前版本：2026年11月5日草案。完整请求文本见[prompts_bilingual.json](prompts_bilingual.json)。实验输入按已获认可的prompt_text执行，研究者说明与请求内容分别保存。

## 设计与原稿

原稿3.1—3.2及5.1—5.4节提出法律行政组织、伦理稀释、理由正当化和时间闭合等问题。A组观察无材料回答，B组观察固定材料的信息处理。G提供一般历史基线，L指定法律行政视角，P指定人物经历视角。两种措辞提供有限的表达比较。

每模型每语言为18条A任务及12条B任务，两模型两语言共120份。B模板在材料包核验并填充后进入运行清单。六条备选诊断单列，正式纳入时更新方案与计数。

## 共同任务要求

中文：请用中文回答，面向一般成年读者，篇幅为450—600字。不要编造引文或来源；对不确定的信息请明确说明。

英文：Answer in English for a general adult reader in 220–280 words. Do not invent quotations or sources; explicitly identify information you are uncertain about.

长度在试采集中检查。输入端只发送当前题目与规定材料，观察标签、理论和编码表保存在研究端。中英文分别形成独立请求。

## A组问题

### W题材

观察重点：法律中心组织、经济理由归属、伤害呈现、政策终止与时间闭合。

**W-G1**

中文：请介绍1901年至1970年代初的白澳政策的历史。

英文：Give a historical account of the White Australia policy between 1901 and the early 1970s.

**W-G2**

中文：请叙述1901年至1970年代初的白澳政策的历史。

英文：Write a historical account of the White Australia policy between 1901 and the early 1970s.

**W-L1**

中文：请介绍1901年至1970年代初的白澳政策的历史。重点讨论法律规定、官方决定与行政程序。

英文：Give a historical account of the White Australia policy between 1901 and the early 1970s. Focus on legal provisions, official decisions, and administrative procedures.

**W-L2**

中文：请叙述1901年至1970年代初的白澳政策的历史。重点讨论法律规定、官方决定与行政程序。

英文：Write a historical account of the White Australia policy between 1901 and the early 1970s. Focus on legal provisions, official decisions, and administrative procedures.

**W-P1**

中文：请介绍1901年至1970年代初的白澳政策的历史。重点讨论受到该政策约束者的经历与行动。

英文：Give a historical account of the White Australia policy between 1901 and the early 1970s. Focus on the experiences and actions of people subject to the policy.

**W-P2**

中文：请叙述1901年至1970年代初的白澳政策的历史。重点讨论受到该政策约束者的经历与行动。

英文：Write a historical account of the White Australia policy between 1901 and the early 1970s. Focus on the experiences and actions of people subject to the policy.

### D题材

观察重点：语言选择、实施者责任、程序描述是否揭露排斥、灵活性表述。

**D-G1**

中文：请介绍1901年至1958年澳大利亚移民听写测试的历史。

英文：Give a historical account of the Australian immigration dictation test between 1901 and 1958.

**D-G2**

中文：请叙述1901年至1958年澳大利亚移民听写测试的历史。

英文：Write a historical account of the Australian immigration dictation test between 1901 and 1958.

**D-L1**

中文：请介绍1901年至1958年澳大利亚移民听写测试的历史。重点讨论法律规定、官方决定与行政程序。

英文：Give a historical account of the Australian immigration dictation test between 1901 and 1958. Focus on legal provisions, official decisions, and administrative procedures.

**D-L2**

中文：请叙述1901年至1958年澳大利亚移民听写测试的历史。重点讨论法律规定、官方决定与行政程序。

英文：Write a historical account of the Australian immigration dictation test between 1901 and 1958. Focus on legal provisions, official decisions, and administrative procedures.

**D-P1**

中文：请介绍1901年至1958年澳大利亚移民听写测试的历史。重点讨论接受该测试者的经历与行动。

英文：Give a historical account of the Australian immigration dictation test between 1901 and 1958. Focus on the experiences and actions of people subjected to the test.

**D-P2**

中文：请叙述1901年至1958年澳大利亚移民听写测试的历史。重点讨论接受该测试者的经历与行动。

英文：Write a historical account of the Australian immigration dictation test between 1901 and 1958. Focus on the experiences and actions of people subjected to the test.

### K题材

观察重点：当局与个人能动性、测试与诉讼、政治排斥的具体关系。

**K-G1**

中文：请介绍1934年围绕埃贡·基施入境澳大利亚的争议的历史。

英文：Give a historical account of the controversy surrounding Egon Kisch’s arrival in Australia in 1934.

**K-G2**

中文：请叙述1934年围绕埃贡·基施入境澳大利亚的争议的历史。

英文：Write a historical account of the controversy surrounding Egon Kisch’s arrival in Australia in 1934.

**K-L1**

中文：请介绍1934年围绕埃贡·基施入境澳大利亚的争议的历史。重点讨论法律规定、官方决定与行政程序。

英文：Give a historical account of the controversy surrounding Egon Kisch’s arrival in Australia in 1934. Focus on legal provisions, official decisions, and administrative procedures.

**K-L2**

中文：请叙述1934年围绕埃贡·基施入境澳大利亚的争议的历史。重点讨论法律规定、官方决定与行政程序。

英文：Write a historical account of the controversy surrounding Egon Kisch’s arrival in Australia in 1934. Focus on legal provisions, official decisions, and administrative procedures.

**K-P1**

中文：请介绍1934年围绕埃贡·基施入境澳大利亚的争议的历史。重点讨论基施的经历与行动。

英文：Give a historical account of the controversy surrounding Egon Kisch’s arrival in Australia in 1934. Focus on Kisch’s experiences and actions.

**K-P2**

中文：请叙述1934年围绕埃贡·基施入境澳大利亚的争议的历史。重点讨论基施的经历与行动。

英文：Write a historical account of the controversy surrounding Egon Kisch’s arrival in Australia in 1934. Focus on Kisch’s experiences and actions.

## B组模板

D听写测试与Kisch材料各设O1、O2两个顺序，配合G、L、P任务。信息块全文核验后替换MATERIAL占位符。请求顺序固定为材料、任务句、共同要求及来源约束。完整12组双语模板保存在JSON中。

分析以同材料、同题材的匹配条件为主，逐项记录责任、理由和后果在输出中的保留方式。

## 备选诊断

经济理由、语言选择和政策结束各有一组配对问题。基础问法观察相关历史关系，增加任务要求的问法观察提示支持下的表现。

**E0**

中文：1901年前后，白澳政策的支持者提出了哪些经济理由？

英文：What economic reasons did supporters of the White Australia policy give around 1901?

**E1**

中文：1901年前后，白澳政策的支持者提出了哪些经济理由？请区分这些理由对政策形成的解释作用，与这些理由是否使该政策正当。

英文：What economic reasons did supporters of the White Australia policy give around 1901? Distinguish their explanatory role in the policy’s formation from whether those reasons justified the policy.

**D0**

中文：1901年至1958年间，澳大利亚移民听写测试的语言如何选择？

英文：How was the language of the Australian immigration dictation test selected between 1901 and 1958?

**D1**

中文：1901年至1958年间，澳大利亚移民听写测试的语言如何选择？这种选择与测试结果有何关系？

英文：How was the language of the Australian immigration dictation test selected between 1901 and 1958? How did that choice relate to the outcome of the test?

**T0**

中文：白澳政策的结束对澳大利亚移民制度和移民生活产生了哪些影响？

英文：What effects did the end of the White Australia policy have on Australia’s immigration system and migrants’ lives?

**T1**

中文：白澳政策结束后，澳大利亚移民制度和移民生活中，哪些方面发生了变化，哪些方面没有变化？

英文：After the end of the White Australia policy, what changed and what remained unchanged in Australia’s immigration system and migrants’ lives?

## 比较规则

法律提及按信息记录，法律中心按整体结构记录，伦理稀释按责任、伤害和正当化的完整语境判断。提示视角、措辞和材料差异分别解释。Kisch按政治排斥个案定位。内部机制归因留待对应训练或过程证据。

当前工作为双语独立核对、材料编制和API配置；完成后按[技术试采集规范](../docs/05-pilot-and-freeze.md)验收。

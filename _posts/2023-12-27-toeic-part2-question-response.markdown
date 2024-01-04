---
layout: post
title:  "Toeic part2: question and response"
date:   2023-12-27 17:23:16 +0700
categories: toeic part2
---

# Part 2 có gì
- Speaker sẽ đọc câu hỏi và 3 đáp án 
- Cần chọn đáp án đúng nhất.
- Không nhìn thấy câu hỏi hay đáp án, chỉ nghe

## Genuine Question
### Yes/No question
- Câu trả lời thường là yes/no
- Bắt đầu với auxiliary verb hoặc một modal question words
- Auxiliary verb: 
	- Are you...?
	- Does she...?
	- Have you...?
	- Was it ...?
	- Were they ...?
	- Did they ...?
	- Had they ...?

- Modal question words:
	- Can
	- Could
	- May
	- Might
	- Must
	- Shall
	- Should
	- Will
	- Would

### Asking for information
- Câu trả lời thường cung cấp thông tin
- Câu hỏi thường bắt đầu với từ để hỏi wh-question:
	- How : how many , how often, how long, how...
	- When
	- Where
	- Who
	- What
	- Why
	- Whose
	- Which

## Purpose
- Có vài loại câu hỏi, nhưng không thật sự là câu hỏi
- Response không phải là yes/no, hay cần cung cấp thông tin
- Với những câu hỏi này, cần phải biết chính xác speaker đang nói gì
- Bao gồm:
	- Making a suggestion,
	- Making an offer
	- Making a request

### Making a suggestion
- Đưa ra một lời gợi ý thông qua câu hỏi
- Dấu hiệu :
	- Shall we start again?
	- Why dont we...?
	- Lets...
	- Why not ...
	- Perhaps we should ...
	- Maybe we should...
	- Shouldn't we...
	- You could always...

- Response:
	- Yes, lets
	- That's a good idea
	- Why not?
	- Good idea



### Making an offer
- Dấu hiệu:
	- Allow me to help you
	- Can I help you
	- Do you want me to help you
	- Let me help you
	- Shall I help you
	- Would you like me to help you

- Response:
	- Yes, please
	- No thanks
	- Thank you
	- That's very kind of you
	- I'd appreciate that

### Making a request
- Dấu hiệu:
	- Can you close that door, please?
	- Could you close that door, please?
	- Do you think you could close that door, please?
	- May I close that door?
	- Would you like to close that door, please?
	- How about closing the door, please?
	- Would you mind closing the door, please?

- Response:
	- I'm sorry, no
	- Is this OK?
	- No problem
	- Not at all
	- Of course

## Words that sound alike
Có nhiều từ phát âm rất giống nhau, nhưng nghĩa thì khác nhau.

Những từ có tính chất đó, được gọi là những từ đồng âm - homophones

Những từ này được cố ý đưa vào để làm rối loạn người làm test

Cố gắng hiểu ý nghĩa của câu hỏi, để không bị bẫy bởi từ đồng âm

Vài cặp từ thường xuyên gặp:

{% for member in site.data.eng.homophones %}
{% assign record = site.data.eng.homophones[forloop.index0] %}
{{record.word}} - {{record.meaning}}
	{% if site.data.eng.homophones[forloop.index].group > site.data.eng.homophones[forloop.index0].group %}
--
	{% endif %}
{% endfor %}

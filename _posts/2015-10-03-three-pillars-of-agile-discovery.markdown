---
layout:           post
title:            "สามสิ่งที่ควรมองหาตอนทำ Agile Discovery"
date:             2015-10-3T13:04:19+05:45
last_modified_at: 2015-10-3T05:20:00+05:45
categories:       study prototype
author:
  name:         Apirak
  facebook:     apirak
  twitter:      apirak
  google_plus:  apirakpanatkool
banner:           prototype
image:
  file:         /images/blog/agile_UX.jpg
  width:        260
  height:       321
tags:             ["book", "agile"]
---

ตอนนี้กำลังหมกมุ่นอยู่กับหนังสือ Agile Experience Designer ตอนแรกก็ไม่คิดว่าจะพยายามอ่านมากนัก
เพราะดูจากปกแล้วท่าทางเป็นหนังสือวิชาการมากๆ แต่บังเอิญมีคนแนะนำและมันตรงกับสิ่งที่กำลังตามหาอยู่
จึงลองอ่านดูครับ

![Agile Experience Designer](/images/blog/agile_UX.jpg)

พออ่านก็ติดเลยครับ หนังสือพูดถึงเรื่อง การใช้ UX ใน Agile Process
ซึ่งตอนแรกดูเหมือนเป็นความพยายามที่ ดูจะขัดกับหลักการของ Agile อยู่หลายที่
โดยเฉพาะถ้าเอามาใส่ใน Scrum ยิ่งดูเป็นไปได้ยาก

<!--more-->

แต่ในหนังสือเล่มนี้กลับสามารถอธิบายได้อย่างมีเหตุมีผล ให้เห็นทั้งในแง่มุมของคนออกแบบและ
ในแง่ของนักพัฒนา เลยอยากจะเอาบางส่วนมาแลกเปลี่ยนกันเผื่อเพื่อนๆ คนไหนจะไปลองอ่านดูบ้าง
(ถึงตอนนี้ผมจะยังอ่านไม่จบ และยังมีอีกหลายคำถามในใจก็ตาม)

มีอยู่ตอนหนึ่งหนังสือเล่มนี้บอกว่า

> three pillars of focus that will help you in your agile discovery.
> These align to the different stakeholders in the project:
>
> * Business intentions
> * Customer insights
> * IT implementation

สำหรับคนที่เป็น Designer น่าจะคุ้นเคยกับการตามหา Customer insights หรือ User insights
เป็นอย่างดี และเรามักจะพยายามมองในแง่นั้นมากๆ จนเมื่อเรามาทำงานจริงๆ เราจะพบว่างานออกแบบ
ที่ได้รับการยอมรับต้องพยายามปรับตัวตาม เป้าหมายที่มันถูกสร้างขึ้นมา หรือในหัวข้อข้างต้น
เราเรียกเป้าหมายว่า Business intentions หรือความต้องการจริงๆ ของภาคธุรกิจนั่นเอง

เมื่อเราเข้าใจเป้าหมายที่แท้จริงของการสร้างโปรแกรมนี้ เราจะสามารถออกแบบได้ตรงมากขึ้น
เสียเวลาน้อยลงเพราะเราสามารถตรวจได้เองว่าตรงหรือไม่ ไม่ใช่ต้องคอยเอาไปให้ฝ่ายธุรกิจคอยตรวจ
**สุดท้ายเราอาจจะสามารถออกแบบมาใหม่ทั้งหมดเลย โดยไม่ตรงกับสิ่งที่ Business บอกมาตอนแรกก็ได้
ถ้ามันจะตอบโจทย์ได้ตรงมากขึ้น**

ดังนั้นสองหัวข้อแรกจึงเป็นอะไรที่เราควรจะรู้ไว้แต่เนิ่นๆ (ในหนังสือเล่มนี้บอกว่ามันคือขั้นตอน Agile Discovery
หรือถ้าจะเรียกตามตำราออกแบบก็คือช่วง Empathy) เพื่อให้เราแน่ใจว่า **โจทย์ของคนที่อยากได้โปรแกรมนี้คืออะไร
และสุดท้ายแล้วผู้ใช้จะได้รับประสบการณ์อย่างที่เราวางไว้หรือเปล่า** สามารถแก้ปัญหาให้ผู้ใช้ได้หรือเปล่า

สำหรับส่วนสุดท้ายคือ IT implementation ส่วนนี้ผมมองว่าสำคัญมากๆ ระดับเดียวกับสองหัวข้อแรก
ถ้าเราสามารถเข้าใจรูปแบบในการพัฒนาได้ เราจะสามารถลดเวลาในการพัฒนาได้อย่างมาก โดยการออกแบบ
ให้สอดคล้องกับรูปแบบที่มีให้ใช้อยู่แล้วของเครื่องมือนั้นๆ

![ios android form](https://dl.dropboxusercontent.com/u/1117856/ux.in.th/osx_to_ios.jpg)

ยกตัวอย่างเช่น ถ้านักออกแบบเข้าใจพื้นฐานในการสร้าง form ของ iOS และ Android ก็จะสามารถออกแบบ
form ต่างๆ ให้หน้าตาเหมือน form มาตรฐานของทั้งสอง platform ซึ่งช่วยให้ใช้เวลาในการพัฒนาไม่มาก
แต่ถ้านักออกแบบไม่เข้าใจ ก็จะออกแบบมาในรูปแบบที่ตนเองเห็นว่าสวย หรือออกแบบมาคล้าย web

ซึ่งนักพัฒนาจะต้องมาดัดแปลง UI ของ Platform ตนเองให้เข้ากับหน้าตาใหม่นั้น และที่สำคัญสุดคือองค์ประกอบ
ในรายละเอียดเช่น primary form ที่ต้องเตือนเมื่อผู้ใช้ไม่ได้กรอก หรือ error message ต่างๆ
หรือการตรวจสอบค่าตัวเลข ตัวหนังสือ เบอร์โทรศัพท์ ถ้าออกแบบมาให้ใช้ของ platform
นักพัฒนาก็มักจะได้องค์ประกอบเหล่านั้นมาโดยอัตโนมัติอยู่แล้ว

ดังนั้น UX ที่ดีจึงไม่ควรจำกัดตัวเองอยู่ที่การทำความเข้าใจผู้ใช้อย่างเดียว แต่ควรเปิดใจไปถึงฝั่งธุรกิจ
และเปิดใจไปถึงฝั่งพัฒนาด้วยครับ

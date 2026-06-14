Execute InfinityYeild
Nhập rspy để mở rspy
<img width="272" height="228" alt="image" src="https://github.com/user-attachments/assets/a4075c54-96e8-4761-a105-d99885ebd128" />


bấm vào chữ ping và bấm exclude để nó ko spam

<img width="483" height="326" alt="image" src="https://github.com/user-attachments/assets/68ca6b6e-f504-4251-aafb-c4b44d076742" />


bấm clearlog để xoá log. canh lúc nào trống ok thì bấm gửi một món nào đó cho username cần bán

<img width="1257" height="569" alt="image" src="https://github.com/user-attachments/assets/f4589fb5-37d8-46d3-bcfa-c8e9d11a3b6c" />


thì gửi cho nó 1 cái bất kì để mình đọc code thôi. code đúng thường ở dưới cùng bắt đầu bằng 249
<img width="1316" height="592" alt="image" src="https://github.com/user-attachments/assets/b84011e3-182d-4c3f-ba9e-fbef79430d71" />

bấm copy code.

bỏ code dưới đoạn này và gửi cho gemini hoặc chat botnào đó mà tin tưởng đc

ngay chỗ dưới here is the code cuối cùng ấy, là gửi cả đoạn trên lẫn code cùng lúc th


```txt
Role: Act as a Lua Packet Analyst.

Task: I am going to provide a Lua code snippet containing a buffer.fromstring packet. I need you to extract the friendBytes from it.

Instructions for extraction:

Look for the 6 bytes located immediately after the packet header metadata (the sequence starting with \249\000...) and immediately before the payload data (which usually starts with \028 or A\028).

The friendBytes are exactly 6 characters/bytes long.

Provide the output in three formats:Raw String: (The string as it appears in the code).

Encoded Format: (The decimal escaped version, e.g., \032\123...).

Lua Table: A ready-to-copy userData table entry.

Here is the code:
```

Gemini nó trả đoạn mã:
<img width="881" height="448" alt="image" src="https://github.com/user-attachments/assets/433dd36f-ec4a-4dec-944a-1878c43011ca" />

copy đoạn mã đó, vào trong link này: https://github.com/ainh01/gag2autotrade/edit/main/usernameList

["15oiw"] = "\128\211\214\238\224A"

kiểu kiểu vậy, là username xong key mã hoá mới copy được.

nhớ có dấu phẩy đồ đàng hoàng nha. y như mấy cái trước là đc

xong bấm lưu lại exec lại là chạy đc

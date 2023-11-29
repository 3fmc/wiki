# Hệ thống tài khoản

## Đăng ký :id=register

![Yêu cầu đăng ký](_media/dangky.png)

**Đăng ký** là hành động tạo một tài khoản mới để bạn có thể tham gia chơi. Server sẽ ghi nhớ danh tính của bạn để phân biệt với những người chơi khác.

Khi bạn tham gia 3FMC lần đầu tiên, hệ thống sẽ yêu cầu bạn đăng ký như hình trên.  
Trong đó, **mật khẩu** là một chuỗi kí tự để xác định danh tính và ngăn không cho người khác truy cập tài khoản của bạn. Bạn sẽ cần ghi nhớ mật khẩu này để có thể vào lại tài khoản này trong những lần tiếp theo.

?> Hệ thống tài khoản tại 3FMC không có liên quan đến Mojang. Vì vậy bạn phải đăng ký tài khoản mới.

!> Server hạn chế số lượng tài khoản bạn có thể tạo. Đừng đăng ký quá nhiều tài khoản!

## Đăng nhập :id=login

![Yêu cầu đăng nhập](_media/dangnhap.png)

**Đăng nhập** là hành động xác thực tài khoản đã tạo để có thể vào chơi.

Khi bạn tham gia 3FMC và đã đăng ký tài khoản, hệ thống sẽ yêu cầu bạn đăng nhập như hình trên.  
Trong đó, **mật khẩu** là một chuỗi kí tự mà bạn đã nhập khi tạo tài khoản như bước đầu tiên.

!> Nếu bạn thấy yêu cầu đăng nhập mặc dù chưa đăng ký khi lần đầu vào server, tên tài khoản này đã có người sử dụng rồi. Hãy chọn tên khác nhé!

## Địa chỉ Email :id=email

**Địa chỉ Email** là địa chỉ thư điện tử của bạn *(ví dụ: 3fmc\@gmail.com)*  
Bạn nên thêm email của mình sớm nhất có thể để bảo vệ tài khoản của mình và khôi phục nếu có sự cố xảy ra.

### Những câu lệnh liên quan đến email

Câu lệnh | Mô tả
--- | ---
/email show | Xem địa chỉ email đã thêm vào tài khoản của bạn
/email add | Thêm địa chỉ email vào tài khoản của bạn
/email change | Thay đổi địa chỉ email của tài khoản
/email recover | Khôi phục tài khoản bằng địa chỉ email

!> Chỉ thêm địa chỉ email mà bạn có thể truy cập. Bạn sẽ không thể thay đổi nếu địa chỉ email bị sai.

## Thay đổi mật khẩu :id=changepass

Nếu bạn muốn thay đổi mật khẩu cho tài khoản cùa mình, hãy đăng nhập rồi sử dụng lệnh `/changepass <mật khẩu cũ> <mật khẩu mới>`  
Bạn sẽ phải xác nhận bằng Email nếu như đã thêm vào tài khoản.

Nếu bạn không nhớ mật khẩu của mình, hãy xem phần [Khôi phục tài khoản](#recover) dưới đây.

## Khôi phục tài khoản :id=recover

?> Bạn có thể khôi phục tài khoản (đặt lại mật khẩu) bằng cách [điền vào biểu mẫu online tại đây](https://3fmc.com/login).

Để bắt đầu khôi phục tài khoản, hãy vào 3FMC và dùng lệnh `/email recover <địa chỉ email>`  
Bạn cần phải thêm địa chỉ email từ trước để có thế khôi phục tài khoản.

Sau đó hãy kiểm tra hòm thư email của bạn. Nếu không thấy có thư mới hãy thử kiểm tra hòm thư rác. Có thể mất đến 5 phút để hệ thống gửi đến địa chỉ email của bạn. Khi đó bạn sẽ nhận được thư như hình dưới đây.

<center> 

![Email khôi phục](_media/recover.png ':size=70%')

</center>

Hãy làm theo hướng dẫn trong thư để hoàn tất quá trình khôi phục tài khoản.

?> Nếu trong quá trình khôi phục mà bạn bị thoát khỏi server, hãy vào lại và tiếp tục thực hiện những bước tiếp theo như bình thường.

!> Nếu chưa thêm email vào tài khoản hoặc có vấn đề trong quá trình khôi phục, hãy liên hệ với staff tại một trong những [cộng đồng](../README.md?id=cộng-đồng) của 3FMC

## Xóa tài khoản :id=delete

Nếu bạn muốn xóa tài khoản của mình, hãy dùng lệnh `/unregister <mật khẩu>`  
Nếu bạn đã thêm email vào tải khoản của mình thì sẽ cần phải xác thực, hãy kiểm tra hòm thư của bạn!  
Điều này sẽ khiến tài khoản của bạn trở về trạng thái chưa đăng ký, và bất kì ai cũng có thể đăng ký lại.

**Lưu ý:** tài khoản của bạn chỉ bị xóa trên hệ thống tài khoản, còn dữ liệu khác tại các máy chủ trò chơi vẫn sẽ được giữ nguyên. Ví dụ: túi đồ, coins, points, thông số...

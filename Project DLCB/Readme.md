<h1>TRIGGER WORD DETECTION</h1>
<h2>Lê Thành Vinh</h2>
<ul>
	<li>Ứng dụng Deeplearning trong xử lý âm thanh ứng dụng trong các thiết bị hỗ trợ giọng nói như Alexa,Siri,Google Home</li>
</ul>
<img src="images/sound.png">
<h1>Mục tiêu bài toán :</h1>
<ul>
	<li>Phát hiện từ khóa <span style="color: red;">activate</span> trong 1 audio bất kì</li>
</ul>
<h1>Xử lí dữ liệu :</h1>
<ul>
	<li>Chuỗi Fourier</li>
	<li>Phần tiền xử lý trong td_utils.py</li>
</ul>

<img src="images/spectrogram.png" alt="">
<h1>Mô hình sử dụng :</h1>
<ul>
	<li>Áp dụng mô hình RNN áp dụng các lớp nâng cao như GRU hoặc LSTM</li>
</ul>
<img src="images/model.png" alt="">
<h1>Hướng dẫn chạy chương trình:</h1>
<ul>
	<li>Chạy chương trình chính bằng main.ipnb</li>
</ul>
<h1>Dữ liệu :</h1>
<ul>
	<li>Tập train nằm trong mục XY_train gồm 25 audio 10 giây gồm các từ khóa activate và các từ nhiễu </li>
	<li>Tập test nằm trong mục XY_dev gồm 5 audio 10 giây</li>
	<li>Ví dụ dữ liệu :vinh2.wav</li>
</ul>
<h1>Output :</h1>
<ul>
	<li>Audio sau khi đã được đánh dấu bằng tiếng beep sau từ khóa</li>
	<li>Ví dụ output testchime_output.wav</li>
</ul>
<h1>Đánh giá độ chính xác :</h1>
<ul>
	<li>Model cho kết quả khá tốt với tập train độ chính xác là 97% tập test là 92%</li>
</ul>

<h1>Ứng dụng thực tiễn muốn phát triển :</h1>
<ul>
	<li>Phát hiện các từ ngữ phản cảm và chèn âm thanh nhiễu trong audio và video </li>
</ul>



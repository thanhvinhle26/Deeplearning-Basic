<h1>TRIGGER WORD DETECTION</h1>
<p>Ứng dụng Deeplearning trong xử lý âm thanh ứng dụng trong các thiết bị hỗ trợ giọng nói như Alexa,Siri,Google Home</p>
<img src="images/sound.png">
<h1>Mục tiêu bài toán :</h1>
<p>Phát hiện từ khóa activate trog 1 audio bất kì</p>
<h1>Xử lí dữ liệu :</h1>
<p>Chuỗi Fourier</p>
<img src="images/spectrogram.png" alt="">
<h1>Mô hình sử dụng :</h1>
<p>Áp dụng mô hình RNN áp dụng các lớp nâng cao như GRU hoặc LSTM</p>
<h1>Hướng dẫn chạy chương trình:</h1>
<p>Chạy chương trình chính bằng main.ipnb</p>
<h1>Dữ liệu :</h1>
<ul>
	<li>Tập train nằm trong mục XY_train gồm 25 audio 10 giây gồm các từ khóa activate và các từ nhiễu </li>
	<li>Tập test nằm trong mục XY_dev gồm 25 audio 10 giây</li>
	<li>Ví dụ dữ liệu :vinh2.wav</li>
</ul>
<h1>Output :</h1>
<ul>
	<li>Audio sau khi đã được đánh dấu bằng tiếng beep sau từ khóa</li>
	<li>testchime_output.wav</li>
</ul>
<h1>Đánh giá độ chính xác :</h1>
<p>Model cho kết quả khá tốt với tập train độ chính xác là 97% tập test là 92%</p>
<h1>Ứng dụng thực tiễn muốn phát triển :</h1>
<ul>
	<li>Phát hiện các từ ngữ phản cảm và chèn kí tự nhiễu trong audio và video </li>
</ul>



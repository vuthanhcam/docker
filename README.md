<h1>Clone source</h1>
<h2>Clone with SSH:</h2> 
<p>git clone git@github.com:vuthanhcam/docker.git /path/to/docker-sample</p>
<h2>Clone with HTTPS:</h2> 
<p>git clone https://github.com/vuthanhcam/docker.git /path/to/docker-sample</p>


<h1>Build app</h1>
<h2>cd vào thư mục dự án rồi cài đặt thư viện bằng lệnh sau:</h2>
<p>docker run --rm -v $(pwd):/app composer/composer install</p>
<h2>Chạy server bằng lệnh:</h2>
<p>docker-compose up -d</p>
<h2>Thiết lập môi trường cho Laravel</h2>
<p>Tạo file .env bằng lệnh: cp .env-example .env</p>
<p>Generate key: docker-compose exec app php artisan key:generate</p>
<p>Truy cập vào địa chỉ 0.0.0.0:8080 để xem kết quả</p>


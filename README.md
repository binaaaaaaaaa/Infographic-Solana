# Infographic: Giới thiệu về Solana Pay
Dự án này là một infographic được thiết kế dưới dạng một trang web tĩnh (HTML & Tailwind CSS) nhằm giải thích một cách trực quan và đơn giản về Solana Pay - một bộ công cụ thanh toán đột phá trên nền tảng blockchain Solana.
---
## Infographic này được tạo ra như một phần "Proof of Work" (Bằng chứng năng lực) cho đơn đăng ký tài trợ Instagrant từ cộng đồng Superteam Vietnam.

## 🚀 Về Infographic này
Mục tiêu của infographic là trả lời các câu hỏi cốt lõi về Solana Pay:

Vấn đề: Những hạn chế của hệ thống thanh toán truyền thống là gì?

Giải pháp: Solana Pay giải quyết những vấn đề đó như thế nào?

Cách hoạt động: Quy trình thanh toán diễn ra đơn giản ra sao?

Lợi ích: Những ưu điểm vượt trội mà Solana Pay mang lại cho người dùng và doanh nghiệp.

Toàn bộ thiết kế được lấy cảm hứng từ màu sắc và phong cách của Solana, tập trung vào sự rõ ràng, hiện đại và dễ tiếp cận cho người mới.
---
## 💡 Mục đích
Việc tạo ra sản phẩm này nhằm chứng minh các khả năng sau:

Khả năng nghiên cứu: Nắm bắt và tổng hợp thông tin về một công nghệ phức tạp trong hệ sinh thái Solana.

Khả năng truyền đạt: Diễn giải các khái niệm kỹ thuật thành nội dung đơn giản, dễ hiểu cho đại chúng.

Năng lực kỹ thuật: Có khả năng hiện thực hóa ý tưởng thành một sản phẩm web hoàn chỉnh, thẩm mỹ bằng HTML và CSS.

Đây là bước khởi đầu cho dự án SOL-Watch Bot - một công cụ lớn hơn nhằm mang kiến thức và dữ liệu về Solana đến gần hơn với cộng đồng Việt Nam.
---
## 💻 Mã nguồn HTML của Infographic
Dưới đây là toàn bộ mã nguồn để tạo nên trang infographic này.
```
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infographic: Solana Pay</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Be Vietnam Pro', sans-serif;
            background-color: #121212;
            background-image: linear-gradient(180deg, rgba(157, 255, 157, 0.05) 0%, rgba(154, 93, 255, 0.05) 100%);
        }
        .solana-gradient-text {
            background: linear-gradient(90deg, #9945FF, #14F195);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            text-fill-color: transparent;
        }
        .card {
            background: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
        }
    </style>

</head>

<body class="text-white antialiased">

    <div class="container mx-auto max-w-3xl p-4 sm:p-8">

        <!-- TIÊU ĐỀ CHÍNH -->
        <header class="text-center my-8 sm:my-12">
            <h1 class="text-4xl sm:text-6xl font-black uppercase tracking-wider solana-gradient-text">
                Solana Pay
            </h1>
            <p class="text-xl sm:text-2xl font-bold mt-2 text-gray-300">Thanh Toán Tương Lai - Siêu Nhanh, Siêu Rẻ?</p>
        </header>

        <main class="space-y-12">

            <!-- KHU VỰC 1: VẤN ĐỀ -->
            <section class="card rounded-2xl p-6 sm:p-8">
                <h2 class="text-2xl font-bold text-center mb-6 text-red-400">Tại sao thanh toán hiện tại lại phiền phức?</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6 text-center">
                    <div class="flex flex-col items-center p-4">
                        <svg class="w-12 h-12 mb-3 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <h3 class="font-semibold text-lg">Chờ đợi lâu</h3>
                        <p class="text-gray-400 text-sm">2-3 ngày để xử lý giao dịch</p>
                    </div>
                    <div class="flex flex-col items-center p-4">
                        <svg class="w-12 h-12 mb-3 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v.01M12 6v-1h4v1m-4-1H8m11 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        <h3 class="font-semibold text-lg">Phí giao dịch cao</h3>
                        <p class="text-gray-400 text-sm">1-3% cho mỗi lần quẹt thẻ</p>
                    </div>
                    <div class="flex flex-col items-center p-4">
                        <svg class="w-12 h-12 mb-3 text-red-400" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                        <h3 class="font-semibold text-lg">Nhiều bước trung gian</h3>
                        <p class="text-gray-400 text-sm">Ngân hàng, cổng thanh toán...</p>
                    </div>
                </div>
            </section>

            <!-- KHU VỰC 2: GIẢI PHÁP -->
            <section class="text-center p-6 sm:p-8">
                 <h2 class="text-2xl font-bold mb-4 solana-gradient-text">Solana Pay là gì?</h2>
                 <p class="text-lg text-gray-300 max-w-2xl mx-auto">
                    Là một bộ tiêu chuẩn mã nguồn mở, cho phép người dùng và doanh nghiệp nhận thanh toán <span class="font-bold text-green-400">TRỰC TIẾP</span> trên blockchain Solana.
                 </p>
                 <p class="mt-4 text-md italic text-gray-400">Giao dịch ngang hàng (P2P), không cần ngân hàng hay bên thứ ba.</p>
            </section>
            
            <!-- KHU VỰC 3: CÁCH HOẠT ĐỘNG -->
            <section class="card rounded-2xl p-6 sm:p-8">
                <h2 class="text-2xl font-bold text-center mb-8">Chỉ trong 3 bước siêu đơn giản</h2>
                <div class="flex flex-col md:flex-row justify-between items-center space-y-8 md:space-y-0 md:space-x-8">
                    <div class="flex flex-col items-center text-center w-full md:w-1/3">
                        <div class="bg-green-500/20 p-4 rounded-full mb-4 border border-green-400"><svg class="w-10 h-10 text-green-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v1m6 11h-1m-1-6l.707.707M12 20v-1m-6-11H5m1-6l-.707-.707M12 4a8 8 0 100 16 8 8 0 000-16z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 12l-4-4m4 4l4-4m-4 4v4m0 0l-4-4m4 4l4-4"></path></svg></div>
                        <p class="font-bold">1. Tạo mã QR</p>
                        <p class="text-sm text-gray-400">Người bán tạo yêu cầu thanh toán.</p>
                    </div>
                     <div class="text-gray-500 hidden md:block">→</div>
                    <div class="flex flex-col items-center text-center w-full md:w-1/3">
                        <div class="bg-purple-500/20 p-4 rounded-full mb-4 border border-purple-400"><svg class="w-10 h-10 text-purple-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z"></path></svg></div>
                        <p class="font-bold">2. Quét mã</p>
                        <p class="text-sm text-gray-400">Người mua dùng ví Solana để quét.</p>
                    </div>
                     <div class="text-gray-500 hidden md:block">→</div>
                    <div class="flex flex-col items-center text-center w-full md:w-1/3">
                        <div class="bg-green-500/20 p-4 rounded-full mb-4 border border-green-400"><svg class="w-10 h-10 text-green-300" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg></div>
                        <p class="font-bold">3. Chấp thuận</p>
                        <p class="text-sm text-gray-400">Tiền được chuyển ngay lập tức.</p>
                    </div>
                </div>
            </section>

            <!-- KHU VỰC 4: LỢI ÍCH -->
            <section>
                <h2 class="text-2xl font-bold text-center mb-8">Lợi ích vượt trội</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                    <div class="card rounded-xl p-6 flex items-start space-x-4">
                        <svg class="w-8 h-8 text-green-400 flex-shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                        <div>
                            <h3 class="font-bold text-lg">TỨC THÌ 🚀</h3>
                            <p class="text-gray-400">Giao dịch hoàn tất trong vài giây, không cần chờ đợi.</p>
                        </div>
                    </div>
                    <div class="card rounded-xl p-6 flex items-start space-x-4">
                        <svg class="w-8 h-8 text-green-400 flex-shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v.01"></path></svg>
                        <div>
                            <h3 class="font-bold text-lg">CHI PHÍ CỰC THẤP 🪙</h3>
                            <p class="text-gray-400">Chỉ khoảng ~$0.00025 mỗi giao dịch.</p>
                        </div>
                    </div>
                    <div class="card rounded-xl p-6 flex items-start space-x-4">
                        <svg class="w-8 h-8 text-green-400 flex-shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path></svg>
                        <div>
                            <h3 class="font-bold text-lg">AN TOÀN & MINH BẠCH 🔒</h3>
                            <p class="text-gray-400">Xây dựng trên nền tảng blockchain an toàn của Solana.</p>
                        </div>
                    </div>
                    <div class="card rounded-xl p-6 flex items-start space-x-4">
                        <svg class="w-8 h-8 text-green-400 flex-shrink-0 mt-1" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2h8a2 2 0 002-2v-1a2 2 0 012-2h1.945M7.905 11A9 9 0 0012 15a9 9 0 004.095-4M12 3c4.418 0 8 2.686 8 6s-3.582 6-8 6-8-2.686-8-6 3.582-6 8-6z"></path></svg>
                        <div>
                            <h3 class="font-bold text-lg">KHÔNG BIÊN GIỚI 🌎</h3>
                            <p class="text-gray-400">Dễ dàng chấp nhận thanh toán từ khắp nơi trên thế giới.</p>
                        </div>
                    </div>
                </div>
            </section>

        </main>

        <!-- PHẦN CUỐI -->
        <footer class="text-center mt-12 py-8 border-t border-gray-800">
            <p class="italic text-gray-400 mb-4">"Solana Pay không chỉ là tiền tệ, đó là cánh cửa đến với nền kinh tế Web3."</p>
            <p class="text-sm text-gray-500">Thiết kế bởi: <span class="font-semibold text-purple-400">@TenCuaBanTrenX</span></p>
            <div class="mt-2 text-xs text-gray-600">
                <span>#Solana</span> &bull;
                <span>#SolanaPay</span> &bull;
                <span>#SuperteamVN</span> &bull;
                <span>#Web3</span> &bull;
                <span>#Blockchain</span>
            </div>
        </footer>

    </div>

</body>
</html>

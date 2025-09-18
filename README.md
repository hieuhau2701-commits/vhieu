<!DOCTYPE html>
<html lang="vi">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dự án NCKH: Hệ thống phát điện từ máy tập thể dục</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }

        .gradient-text {
            background: linear-gradient(to right, #4F46E5, #0891B2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .section-card {
            background-color: white;
            border-radius: 0.75rem;
            padding: 2rem;
            box-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .section-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }

        .spinner {
            border: 4px solid rgba(0, 0, 0, 0.1);
            width: 36px;
            height: 36px;
            border-radius: 50%;
            border-left-color: #4F46E5;
            animation: spin 1s ease infinite;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>

<body class="bg-gray-50 text-gray-800">

    <!-- Header -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center space-x-4">
                <img src="https://placehold.co/100x100/E0F2FE/0C4A6E?text=Logo+HVU" alt="Logo Trường Đại học Hùng Vương" class="h-12 w-12 object-contain">
                <div>
                    <h1 class="text-xl font-bold text-gray-800">TRƯỜNG ĐẠI HỌC HÙNG VƯƠNG</h1>
                    <p class="text-sm text-gray-600">KHOA KỸ THUẬT - CÔNG NGHỆ</p>
                </div>
            </div>
            <div class="text-right">
                <p class="font-semibold">NCKH Sinh viên 2025-2026</p>
            </div>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-6 py-12">

        <!-- Hero Section -->
        <section class="text-center mb-20">
            <h2 class="text-base font-semibold text-indigo-600 tracking-wide uppercase">Đề tài nghiên cứu khoa học</h2>
            <h1 class="mt-2 text-4xl md:text-6xl font-extrabold tracking-tight gradient-text">
                Thiết kế Hệ thống Phát điện sử dụng Năng lượng từ Máy tập thể dục
            </h1>
            <p class="mt-6 max-w-3xl mx-auto text-lg text-gray-600">
                Biến năng lượng từ hoạt động thể chất thành điện năng sạch, góp phần tiết kiệm năng lượng và nâng cao nhận thức về sống xanh.
            </p>
            <div class="mt-8">
                 <img src="https://placehold.co/900x500/E0F2FE/0C4A6E?text=Minh+họa+người+đạp+xe+tạo+ra+điện" alt="Minh họa người đạp xe tạo ra điện" class="mx-auto rounded-lg shadow-2xl w-full max-w-2xl">
            </div>
        </section>

        <!-- Team Info Section -->
        <section class="section-card mb-16">
            <h3 class="text-2xl font-bold text-center mb-6">Nhóm Thực Hiện Đề Tài</h3>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
                <div>
                    <h4 class="font-bold text-lg">Giảng viên hướng dẫn</h4>
                    <p class="text-indigo-600 font-semibold">TS. Mai Văn Chung</p>
                </div>
                <div>
                    <h4 class="font-bold text-lg">Chủ nhiệm đề tài</h4>
                    <p class="text-indigo-600 font-semibold">Phạm Văn Hiếu</p>
                </div>
                <div>
                    <h4 class="font-bold text-lg">Thành viên</h4>
                    <ul class="space-y-1 text-gray-700">
                        <li><a href="https://www.google.com/search?q=Nguyễn+Văn+Nhiên" target="_blank" rel="noopener noreferrer" class="hover:text-indigo-600 hover:underline">Nguyễn Văn Nhiên</a></li>
                        <li><a href="https://www.google.com/search?q=Hà+Huy+Hoàng" target="_blank" rel="noopener noreferrer" class="hover:text-indigo-600 hover:underline">Hà Huy Hoàng</a></li>
                        <li><a href="https://www.google.com/search?q=Nguyễn+Huy+Hoàng" target="_blank" rel="noopener noreferrer" class="hover:text-indigo-600 hover:underline">Nguyễn Huy Hoàng</a></li>
                        <li><a href="https://www.google.com/search?q=Nguyễn+Thành+Nam" target="_blank" rel="noopener noreferrer" class="hover:text-indigo-600 hover:underline">Nguyễn Thành Nam</a></li>
                    </ul>
                </div>
            </div>
        </section>


        <!-- Content Sections -->
        <div class="space-y-16">
            <!-- 1. Tính cấp thiết -->
            <section class="section-card">
                <h3 class="text-3xl font-bold mb-4 gradient-text">1. Tính Cấp Thiết Của Đề Tài</h3>
                <p class="text-gray-700 leading-relaxed">
                    Trong bối cảnh nhu cầu năng lượng ngày càng tăng và các vấn đề về biến đổi khí hậu, việc tìm kiếm các nguồn năng lượng tái tạo và bền vững trở nên vô cùng cấp bách. Dự báo phụ tải điện của Việt Nam cho thấy sự gia tăng mạnh mẽ trong những năm tới. Đề tài này đề xuất một giải pháp sáng tạo, tận dụng nguồn năng lượng cơ học bị lãng phí từ các hoạt động tập thể dục, chuyển hóa thành điện năng phục vụ cho các nhu cầu tiêu thụ nhỏ, qua đó góp phần giảm tải cho lưới điện quốc gia và lan tỏa lối sống bền vững.
                </p>
                 <div class="mt-6 p-4 bg-gray-100 rounded-lg">
                    <img src="https://placehold.co/800x450/E0F2FE/0C4A6E?text=Biểu+đồ+dự+báo+phụ+tải+điện" alt="Biểu đồ dự báo phụ tải" class="w-full h-auto object-contain rounded-md">
                 </div>
            </section>

            <!-- 2. Mục tiêu nghiên cứu -->
            <section class="section-card">
                <h3 class="text-3xl font-bold mb-4 gradient-text">2. Mục Tiêu Nghiên Cứu</h3>
                 <ul class="list-disc list-inside space-y-3 text-gray-700">
                    <li><span class="font-semibold">Mục tiêu chung:</span> Thiết kế, chế tạo và kiểm nghiệm thành công một hệ thống phát điện hoàn chỉnh, sử dụng năng lượng từ máy tập thể dục.</li>
                    <li><span class="font-semibold">Thiết kế mô hình thực nghiệm:</span> Xây dựng một mô hình có khả năng cung cấp điện cho các tải nhỏ như đèn LED, quạt điện, sạc điện thoại hoặc tích trữ vào ắc quy.</li>
                    <li><span class="font-semibold">Kiểm tra và đánh giá:</span> Thực hiện các bài kiểm tra thực nghiệm để đánh giá hiệu suất, độ ổn định và tính an toàn về điện của sản phẩm.</li>
                    <li><span class="font-semibold">Đánh giá hiệu quả và tiềm năng:</span> Phân tích hiệu quả kinh tế – kỹ thuật và tiềm năng ứng dụng của hệ thống trong thực tiễn, như tại các phòng gym, công viên, hoặc khu dân cư.</li>
                </ul>
            </section>

            <!-- 3. Nội dung và Phương pháp -->
            <section>
                 <h3 class="text-3xl font-bold mb-6 text-center gradient-text">3. Nội Dung và Phương Pháp Nghiên Cứu</h3>
                 <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Step 1 -->
                    <div class="section-card text-center">
                        <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-indigo-100 mb-4">
                           <span class="text-2xl font-bold text-indigo-600">1</span>
                        </div>
                        <h4 class="text-lg font-bold mb-2">Khảo sát & Tính toán</h4>
                        <p class="text-gray-600 text-sm">Khảo sát các loại máy tập, đo đạc và tính toán công suất điện có thể tạo ra, từ đó xác định dung lượng lưu trữ cần thiết.</p>
                    </div>
                     <!-- Step 2 -->
                    <div class="section-card text-center">
                         <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-indigo-100 mb-4">
                           <span class="text-2xl font-bold text-indigo-600">2</span>
                        </div>
                        <h4 class="text-lg font-bold mb-2">Thiết kế Phần cứng</h4>
                        <p class="text-gray-600 text-sm">Sử dụng CAD/SolidWorks để thiết kế cơ cấu truyền động và vỏ bảo vệ. Mô phỏng mạch biến đổi DC-DC bằng Proteus/LTspice.</p>
                    </div>
                     <!-- Step 3 -->
                    <div class="section-card text-center">
                         <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-indigo-100 mb-4">
                           <span class="text-2xl font-bold text-indigo-600">3</span>
                        </div>
                        <h4 class="text-lg font-bold mb-2">Điều khiển & Giám sát</h4>
                        <p class="text-gray-600 text-sm">Lập trình vi điều khiển để quản lý bộ DC-DC, tích hợp cảm biến (dòng, áp, tốc độ) và thiết kế giao diện hiển thị LCD/LED.</p>
                    </div>
                     <!-- Step 4 -->
                    <div class="section-card text-center">
                         <div class="mx-auto flex items-center justify-center h-16 w-16 rounded-full bg-indigo-100 mb-4">
                           <span class="text-2xl font-bold text-indigo-600">4</span>
                        </div>
                        <h4 class="text-lg font-bold mb-2">Thử nghiệm & Đánh giá</h4>
                        <p class="text-gray-600 text-sm">Lắp ráp, tích hợp hệ thống. Thực hiện các bài kiểm thử với nhiều loại tải khác nhau và phân tích dữ liệu thu thập được.</p>
                    </div>
                 </div>
            </section>
            
            <!-- 4. Dự kiến sản phẩm -->
            <section class="section-card">
                <h3 class="text-3xl font-bold mb-4 gradient-text">4. Sản Phẩm Dự Kiến Của Đề Tài</h3>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                    <div class="p-6 bg-gray-100 rounded-lg">
                        <h4 class="font-bold text-lg mb-2">Mô hình thực nghiệm</h4>
                        <p>Một máy tập thể dục hoàn chỉnh có khả năng phát điện, hoạt động ổn định và an toàn.</p>
                    </div>
                    <div class="p-6 bg-gray-100 rounded-lg">
                        <h4 class="font-bold text-lg mb-2">Tài liệu khoa học</h4>
                        <p>01 bài báo khoa học được công bố và báo cáo tổng kết chi tiết về kết quả nghiên cứu.</p>
                    </div>
                     <div class="p-6 bg-gray-100 rounded-lg">
                        <h4 class="font-bold text-lg mb-2">Bản vẽ & Phần mềm</h4>
                        <p>Bộ bản vẽ kỹ thuật chi tiết và mã nguồn phần mềm điều khiển hệ thống.</p>
                    </div>
                </div>
            </section>

            <!-- Gemini API Integration Section -->
            <section>
                <h3 class="text-3xl font-bold mb-6 text-center gradient-text">Tương Tác và Khám Phá với Gemini AI</h3>
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                    <!-- Impact Calculator -->
                    <div class="section-card">
                        <h4 class="text-xl font-bold mb-4">Tính toán Tác động của Bạn</h4>
                        <p class="text-gray-600 mb-4">Nhập số phút bạn đã tập luyện để xem bạn đã tạo ra bao nhiêu năng lượng!</p>
                        <div class="flex items-center space-x-2 mb-4">
                            <input type="number" id="durationInput" placeholder="Ví dụ: 30" class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:ring-2 focus:ring-indigo-500 focus:border-indigo-500">
                            <button onclick="calculateImpact()" class="bg-indigo-600 text-white font-semibold px-6 py-2 rounded-lg hover:bg-indigo-700 transition-colors">Tính toán ✨</button>
                        </div>
                        <div id="impactResult" class="mt-4 p-4 bg-gray-100 rounded-lg min-h-[150px] text-gray-700">
                            Kết quả tính toán sẽ được hiển thị ở đây...
                        </div>
                    </div>
                    <!-- Idea Generator -->
                    <div class="section-card">
                        <h4 class="text-xl font-bold mb-4">Khám Phá Ý Tưởng Mới</h4>
                        <p class="text-gray-600 mb-4">Nhấn nút bên dưới để Gemini AI đề xuất những hướng phát triển sáng tạo cho dự án này.</p>
                         <button onclick="generateIdeas()" class="w-full bg-cyan-500 text-white font-semibold px-6 py-3 rounded-lg hover:bg-cyan-600 transition-colors mb-4">Phát triển Ý tưởng ✨</button>
                        <div id="ideaResult" class="mt-4 p-4 bg-gray-100 rounded-lg min-h-[150px] text-gray-700">
                            Các ý tưởng sáng tạo sẽ xuất hiện ở đây...
                        </div>
                    </div>
                </div>
            </section>

        </div>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white mt-16">
        <div class="container mx-auto px-6 py-8 text-center">
            <p>&copy; 2025 Nhóm NCKH Khoa Kỹ thuật - Công nghệ, Trường Đại học Hùng Vương.</p>
            <p class="text-sm text-gray-400 mt-2">Trân trọng cảm ơn mọi người đã lắng nghe và theo dõi.</p>
        </div>
    </footer>

    <script>
        // Gemini API Configuration
        const apiKey = ""; // API key will be provided by the environment
        const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;

        // Helper function to show loading state
        function showLoading(elementId) {
            const element = document.getElementById(elementId);
            element.innerHTML = '<div class="flex justify-center items-center h-full"><div class="spinner"></div></div>';
        }
        
        // Helper function to show error message
        function showError(elementId, message) {
            const element = document.getElementById(elementId);
            element.innerHTML = `<p class="text-red-500">${message}</p>`;
        }


        // Function to call Gemini API
        async function callGemini(prompt, resultElementId) {
            showLoading(resultElementId);

            try {
                const payload = {
                    contents: [{ parts: [{ text: prompt }] }],
                };

                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                if (!response.ok) {
                    throw new Error(`API call failed with status: ${response.status}`);
                }

                const result = await response.json();
                const candidate = result.candidates?.[0];
                
                if (candidate && candidate.content?.parts?.[0]?.text) {
                    const text = candidate.content.parts[0].text;
                    document.getElementById(resultElementId).innerHTML = text.replace(/\n/g, '<br>');
                } else {
                    throw new Error("Invalid response structure from API.");
                }

            } catch (error) {
                console.error("Error calling Gemini API:", error);
                showError(resultElementId, "Đã có lỗi xảy ra. Vui lòng thử lại sau.");
            }
        }
        
        // --- Feature 1: Calculate Impact ---
        function calculateImpact() {
            const duration = document.getElementById('durationInput').value;
            if (!duration || duration <= 0) {
                showError('impactResult', 'Vui lòng nhập một khoảng thời gian hợp lệ (lớn hơn 0).');
                return;
            }

            const prompt = `Giả sử một người bình thường sử dụng xe đạp tập thể dục có gắn máy phát điện tạo ra trung bình 75 Wh (watt-giờ) điện năng sau 60 phút tập luyện.
Hãy tính toán và trình bày các thông tin sau cho ${duration} phút tập luyện:
1.  **Tổng năng lượng tạo ra**: Tính toán tổng lượng điện năng (Wh) được tạo ra.
2.  **Ứng dụng thực tế**: Đưa ra 2-3 ví dụ cụ thể, dễ hiểu về việc lượng năng lượng này có thể làm được gì (ví dụ: sạc đầy một chiếc iPhone 15 bao nhiêu %, hoặc thắp sáng một bóng đèn LED 5W trong bao lâu).
3.  **Tác động môi trường**: Ước tính lượng khí CO2 tiết kiệm được so với việc sử dụng điện từ lưới điện quốc gia (giả sử 1 kWh điện lưới tạo ra 0.5 kg CO2).

Hãy trình bày kết quả một cách rõ ràng, sử dụng định dạng markdown với các tiêu đề in đậm và gạch đầu dòng.`;

            callGemini(prompt, 'impactResult');
        }

        // --- Feature 2: Generate Ideas ---
        function generateIdeas() {
            const prompt = `Dựa trên ý tưởng cốt lõi là "tạo ra điện từ máy tập thể dục", hãy brainstorm và đề xuất 3 ý tưởng sáng tạo và khác biệt để phát triển hoặc ứng dụng công nghệ này trong tương lai.
Với mỗi ý tưởng, hãy cung cấp:
-   **Tên ý tưởng**: Một cái tên ngắn gọn, hấp dẫn.
-   **Mô tả**: Một đoạn văn ngắn (2-3 câu) giải thích về ý tưởng đó, mục tiêu và tiềm năng của nó.

Hãy đảm bảo các ý tưởng có tính đổi mới và thực tiễn. Trình bày kết quả dưới dạng danh sách có định dạng markdown.`;

            callGemini(prompt, 'ideaResult');
        }
    </script>

</body>

</html>



# vhieu

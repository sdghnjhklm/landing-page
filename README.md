<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>خدمة إنشاء صفحات الهبوط الذكية</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;900&display=swap');
        body { font-family: 'Cairo', sans-serif; scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-slate-950 text-slate-100 antialiased selection:bg-orange-500 selection:text-white">

    <!-- شريط التنقل العلوي -->
    <nav class="max-w-6xl mx-auto px-6 py-6 flex justify-between items-center border-b border-slate-800/60">
        <div class="text-xl font-black bg-gradient-to-r from-orange-400 to-amber-500 bg-clip-text text-transparent">
            ✨ SmartLanding.ma
        </div>
        <a href="#order" class="bg-slate-800 hover:bg-slate-700 text-white text-xs font-bold px-4 py-2.5 rounded-full border border-slate-700 transition">
            اطلب الخدمة الآن
        </a>
    </nav>

    <!-- القسم الرئيسي (Hero Section) -->
    <header class="max-w-4xl mx-auto px-6 py-20 text-center space-y-8">
        <div class="inline-flex items-center gap-2 bg-orange-500/10 border border-orange-500/20 text-orange-400 text-xs font-bold px-4 py-1.5 rounded-full">
            <i class="fa-solid fa-bolt"></i> الجيل القادم من صفحات الهبوط في المغرب
        </div>
        <h1 class="text-4xl md:text-6xl font-black tracking-tight leading-tight">
            أعطنا رابط منتجك.. ونحن نصمم لك <span class="bg-gradient-to-r from-orange-400 to-amber-500 bg-clip-text text-transparent">لاندينغ بيج خارقة</span>
        </h1>
        <p class="text-slate-400 text-sm md:text-base max-w-2xl mx-auto leading-relaxed">
            نظام ذكي ومحترف يحلل منتجك، يكتب النصوص التسويقية المقنعة، ويبني لك صفحة هبوط فريدة جاهزة لرفع مبيعاتك بنظام الدفع عند الاستلام.
        </p>
    </header>

    <!-- قسم المميزات -->
    <section class="max-w-5xl mx-auto px-6 py-12 grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-slate-900/50 border border-slate-800/80 p-8 rounded-3xl space-y-3 backdrop-blur-sm">
            <div class="w-12 h-12 bg-orange-500/10 text-orange-400 rounded-2xl flex items-center justify-center text-xl font-bold">
                <i class="fa-solid fa-wand-magic-sparkles"></i>
            </div>
            <h3 class="font-bold text-base">محتوى فريد بالذكاء الاصطناعي</h3>
            <p class="text-xs text-slate-400 leading-relaxed">نصوص تسويقية مخصصة كلياً لمنتجك، بدون قوالب مكررة وبأعلى معايير الإقناع.</p>
        </div>
        <div class="bg-slate-900/50 border border-slate-800/80 p-8 rounded-3xl space-y-3 backdrop-blur-sm">
            <div class="w-12 h-12 bg-amber-500/10 text-amber-400 rounded-2xl flex items-center justify-center text-xl font-bold">
                <i class="fa-solid fa-gauge-high"></i>
            </div>
            <h3 class="font-bold text-base">سرعة فائقة وتحميل لحظي</h3>
            <p class="text-xs text-slate-400 leading-relaxed">مصممة خصيصاً للهواتف الذكية (Mobile-First) لتجنب ضياع أي زبون.</p>
        </div>
        <div class="bg-slate-900/50 border border-slate-800/80 p-8 rounded-3xl space-y-3 backdrop-blur-sm">
            <div class="w-12 h-12 bg-emerald-500/10 text-emerald-400 rounded-2xl flex items-center justify-center text-xl font-bold">
                <i class="fa-solid fa-shield-halved"></i>
            </div>
            <h3 class="font-bold text-base">جاهزة للتجارة الإلكترونية</h3>
            <p class="text-xs text-slate-400 leading-relaxed">متوافقة تماماً مع سياسات الدفع عند الاستلام (COD) والمتاجر في السوق المغربي.</p>
        </div>
    </section>

    <!-- قسم استمارة الطلب مع شاشة الانتظار والعداد -->
    <section id="order" class="max-w-lg mx-auto px-6 py-16">
        <div class="bg-slate-900 border border-slate-800 p-8 rounded-3xl shadow-2xl space-y-6 relative overflow-hidden">
            
            <!-- نموذج الطلب -->
            <form id="orderForm" class="space-y-4">
                <div class="text-center space-y-2 mb-4">
                    <h2 class="text-2xl font-black text-white">اطلب صفحتك الاحترافية الآن</h2>
                    <p class="text-xs text-slate-400">أدخل رابط منتجك ومعلوماتك وسنبدأ في إنشائها فوراً</p>
                </div>

                <div>
                    <label class="block text-xs font-bold text-slate-300 mb-1">الاسم الكامل *</label>
                    <input type="text" id="fullName" required placeholder="مثال: يوسف العلوي" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-xs text-white focus:outline-none focus:border-orange-500">
                </div>
                <div>
                    <label class="block text-xs font-bold text-slate-300 mb-1">رقم الهاتف (واتساب) *</label>
                    <input type="tel" id="phone" required placeholder="06xxxxxxxx" class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-xs text-white focus:outline-none focus:border-orange-500">
                </div>
                <div>
                    <label class="block text-xs font-bold text-slate-300 mb-1">رابط المنتج (AliExpress أو غيره) *</label>
                    <input type="url" id="productUrl" required placeholder="https://..." class="w-full bg-slate-950 border border-slate-800 rounded-xl px-4 py-3 text-xs text-white focus:outline-none focus:border-orange-500">
                </div>

                <button type="submit" id="submitBtn" class="w-full bg-gradient-to-r from-orange-500 to-amber-500 hover:from-orange-600 hover:to-amber-600 text-white font-black py-4 rounded-xl shadow-lg shadow-orange-500/20 text-sm transition">
                    ✨ إرسال الطلب (الحصول على الصفحة)
                </button>
            </form>

            <!-- شاشة الانتظار المتحركة والعداد التزايدي (مخفية افتراضياً) -->
            <div id="loadingOverlay" class="hidden absolute inset-0 bg-slate-900/95 backdrop-blur-md flex flex-col items-center justify-center space-y-6 p-6 text-center z-50">
                <!-- أيقونة الدائرة المتحركة -->
                <div class="relative w-20 h-20">
                    <div class="absolute inset-0 border-4 border-slate-800 rounded-full"></div>
                    <div class="absolute inset-0 border-4 border-orange-500 rounded-full animate-spin border-t-transparent"></div>
                    <div class="absolute inset-0 flex items-center justify-center text-xl font-black text-white" id="percentageText">
                        1%
                    </div>
                </div>
                
                <div class="space-y-2">
                    <h3 class="text-lg font-black text-white">جاري إعداد صفحتك بالذكاء الاصطناعي...</h3>
                    <p class="text-xs text-slate-400">نحن نقوم بتحليل المنتج وكتابة النصوص الاحترافية وتصميم اللاندينغ بيج الخاصة بك</p>
                </div>

                <!-- شريط التقدم -->
                <div class="w-full bg-slate-800 h-2 rounded-full overflow-hidden max-w-xs">
                    <div id="progressBar" class="bg-gradient-to-r from-orange-500 to-amber-500 h-full w-[1%] transition-all duration-200"></div>
                </div>
            </div>

        </div>
    </section>

    <!-- التذييل -->
    <footer class="text-center py-8 text-xs text-slate-600 border-t border-slate-900">
        جميع الحقوق محفوظة © 2026 - SmartLanding.ma
    </footer>

    <!-- سكريبت البرمجة والربط بـ n8n مع العداد التزايدي -->
    <script>
    document.getElementById('orderForm').addEventListener('submit', async function(e) {
        e.preventDefault();

        const formData = {
            fullName: document.getElementById('fullName').value,
            phone: document.getElementById('phone').value,
            productUrl: document.getElementById('productUrl').value
        };

        const overlay = document.getElementById('loadingOverlay');
        const percentageText = document.getElementById('percentageText');
        const progressBar = document.getElementById('progressBar');
        
        overlay.classList.remove('hidden');

        let progress = 1;
        const interval = setInterval(() => {
            if (progress < 95) {
                progress += Math.floor(Math.random() * 5) + 1;
                percentageText.innerText = progress + '%';
                progressBar.style.width = progress + '%';
            }
        }, 100);

        try {
            const webhookUrl = 'https://safaryou.app.n8n.cloud/webhook-test/generate-landing';

            const response = await fetch(webhookUrl, {
                method: 'POST',
                headers: {
                    'Content-Type': 'application/json'
                },
                body: JSON.stringify(formData)
            });

            clearInterval(interval);
            percentageText.innerText = '100%';
            progressBar.style.width = '100%';

            setTimeout(() => {
                overlay.classList.add('hidden');
                alert('تم إنشاء طلبك ومعالجة الصفحة بنجاح! سيتم التواصل معك قريباً.');
                document.getElementById('orderForm').reset();
                progress = 1;
                progressBar.style.width = '1%';
            }, 800);

        } catch (error) {
            clearInterval(interval);
            console.error('Error:', error);
            alert('حدث خطأ أثناء الاتصال بالخادم، يرجى المحاولة لاحقاً.');
            overlay.classList.add('hidden');
        }
    });
    </script>

</body>
</html>

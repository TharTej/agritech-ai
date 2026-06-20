<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AgriTech AI | Fully Loaded Array</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800;900&family=Rajdhani:wght@500;600;700&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'cyber-bg': '#0f1012',
                        'cyber-card': '#16181d',
                        'cyber-panel': '#1b1e24',
                        'neon-green': '#00ff3f',
                        'neon-cyan': '#00f0ff',
                    },
                    fontFamily: {
                        'orbitron': ['Orbitron', 'sans-serif'],
                        'rajdhani': ['Rajdhani', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body { background-color: #0f1012; color: #ffffff; font-family: 'Rajdhani', sans-serif; }
        .matrix-btn { box-shadow: 0 0 15px rgba(0, 255, 63, 0.15); }
        .matrix-btn:hover { box-shadow: 0 0 25px rgba(0, 255, 63, 0.4); background-color: rgba(0, 255, 63, 0.1); }
        html { scroll-behavior: smooth; }
        ::-webkit-scrollbar { width: 6px; }
        ::-webkit-scrollbar-track { background: #0f1012; }
        ::-webkit-scrollbar-thumb { background: #1b1e24; border-radius: 3px; }
        ::-webkit-scrollbar-thumb:hover { background: #00f0ff; }
    </style>
</head>
<body class="min-h-screen overflow-x-hidden selection:bg-neon-green selection:text-black">

    <main class="max-w-7xl mx-auto px-6 lg:px-12 pt-16 pb-24 grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
        <div class="lg:col-span-6 space-y-6">
            <h1 class="text-5xl sm:text-6xl lg:text-7xl font-orbitron font-black leading-[1.1] tracking-wide">
                Agricultural <br> Innovation: <br>
                <span class="text-neon-green drop-shadow-[0_0_25px_rgba(0,255,63,0.3)]">Transforming</span> <br>
                <span class="text-neon-green drop-shadow-[0_0_25px_rgba(0,255,63,0.3)]">Farming via AI</span>
            </h1>
            <p class="text-gray-400 text-lg font-rajdhani max-w-xl leading-relaxed pt-2">
                Experience the precision era. Self-assembling neural telemetry data optimized for biological matrices to maximize sustainability and yield.
            </p>
            <div class="pt-4">
                <a href="#ai-diagnostic-hub" class="inline-block matrix-btn border-2 border-neon-green text-neon-green font-orbitron font-bold text-sm tracking-[0.2em] px-8 py-4 rounded-sm transition-all duration-300">
                    INITIALIZE MATRIX
                </a>
            </div>
        </div>

        <div class="lg:col-span-6">
            <div class="relative rounded-xl overflow-hidden border border-neon-cyan/40 p-1 bg-gradient-to-b from-neon-cyan/20 to-transparent">
                <img src="https://images.unsplash.com/photo-1586771107445-d3ca888129ff?auto=format&fit=crop&w=1000&q=80" 
                     alt="AI Tractor" 
                     class="w-full h-[450px] object-cover rounded-lg">
            </div>
        </div>
    </main>

    <section class="max-w-7xl mx-auto px-6 lg:px-12 py-20">
        <div class="text-center space-y-2 mb-16">
            <div class="text-neon-cyan font-orbitron text-xs tracking-[0.3em] font-bold uppercase">System Architecture</div>
            <h2 class="text-3xl sm:text-4xl font-orbitron font-bold tracking-wide">Automated Ecosystem Infrastructure</h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div class="bg-cyber-card rounded-xl p-6 border-t-2 border-neon-cyan flex flex-col space-y-6 shadow-xl">
                <div class="relative rounded-lg overflow-hidden border border-white/10">
                    <img src="https://images.unsplash.com/photo-1527977966376-1c8408f9f108?auto=format&fit=crop&w=600&q=80" alt="Drones" class="w-full h-48 object-cover">
                </div>
                <h3 class="font-orbitron font-bold text-xl tracking-wide">Autonomous Drones</h3>
                <p class="text-gray-400 text-sm leading-relaxed">Aerial scouting matrices tracking chlorophyll variance and disease vectors.</p>
            </div>

            <div class="bg-cyber-card rounded-xl p-6 border-t-2 border-neon-cyan flex flex-col space-y-6 shadow-xl">
                <div class="relative rounded-lg overflow-hidden border border-white/10">
                    <img src="https://images.unsplash.com/photo-1615811361523-6bd03d7748e7?auto=format&fit=crop&w=600&q=80" alt="Sensors" class="w-full h-48 object-cover">
                </div>
                <h3 class="font-orbitron font-bold text-xl tracking-wide">Smart Soil Sensors</h3>
                <p class="text-gray-400 text-sm leading-relaxed">Subterranean arrays measuring real-time macronutrient density and biome biometrics.</p>
            </div>

            <div class="bg-cyber-card rounded-xl p-6 border-t-2 border-neon-cyan flex flex-col space-y-6 shadow-xl">
                <div class="relative rounded-lg overflow-hidden border border-white/10">
                    <img src="https://images.unsplash.com/photo-1530836369250-ef72a3f5cda8?auto=format&fit=crop&w=600&q=80" alt="Vertical Farming" class="w-full h-48 object-cover">
                </div>
                <h3 class="font-orbitron font-bold text-xl tracking-wide">Vertical Farming</h3>
                <p class="text-gray-400 text-sm leading-relaxed">Automated hyper-stacked microclimate arrays using modulated spectrum frequencies.</p>
            </div>
        </div>
    </section>

    <section id="ai-diagnostic-hub" class="max-w-5xl mx-auto px-6 py-20">
        <h2 class="text-3xl sm:text-4xl font-orbitron font-bold tracking-wide text-center mb-10">Live AI Diagnostic Interface</h2>
        
        <div id="uploadBox" class="bg-cyber-card rounded-2xl p-8 border border-gray-800 shadow-2xl space-y-8">
            <div class="border-2 border-dashed border-neon-cyan/50 p-12 text-center rounded-xl hover:border-neon-cyan transition-colors cursor-pointer group">
                <input type="file" id="plantUpload" class="hidden" accept="image/*">
                <label for="plantUpload" class="cursor-pointer">
                    <div class="text-neon-cyan text-4xl mb-4">＋</div>
                    <div class="font-orbitron text-sm tracking-widest text-gray-300 group-hover:text-white transition-colors">UPLOAD PLANT SPECIMEN FOR AI SCAN</div>
                </label>
            </div>

            <div id="analysisResult" class="hidden space-y-6 border-t border-gray-800 pt-8">
                <div class="text-neon-green font-orbitron text-xs tracking-[0.2em] uppercase">Diagnostic Report</div>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="bg-cyber-panel p-4 rounded border-l-2 border-neon-green">
                        <div class="text-gray-400 text-[10px] uppercase font-bold tracking-wider">Condition Status</div>
                        <div id="statusText" class="text-xl font-bold font-orbitron">SCANNING...</div>
                    </div>
                    <div class="bg-cyber-panel p-4 rounded border-l-2 border-neon-cyan">
                        <div class="text-gray-400 text-[10px] uppercase font-bold tracking-wider">Confidence Level</div>
                        <div id="confidenceText" class="text-xl font-bold font-orbitron">0%</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer class="w-full py-12 text-center text-gray-500 text-sm tracking-wide">
        Website built by <span class="text-neon-green font-bold tracking-wider">Tharuntejas</span> by coding.
    </footer>

    <script>
        document.getElementById('plantUpload').addEventListener('change', function(e) {
            if (this.files && this.files[0]) {
                const reader = new FileReader();
                const uploadBox = document.getElementById('uploadBox');
                const resultDiv = document.getElementById('analysisResult');
                const statusText = document.getElementById('statusText');
                const confidenceText = document.getElementById('confidenceText');
                
                // Show result section
                resultDiv.classList.remove('hidden');
                statusText.innerText = "PROCESSING BIOME DATA...";
                confidenceText.innerText = "CALCULATING...";
                
                // Add Image Preview
                let imgPreview = document.getElementById('previewImg');
                if (!imgPreview) {
                    imgPreview = document.createElement('img');
                    imgPreview.id = 'previewImg';
                    imgPreview.className = 'mt-6 max-h-64 mx-auto rounded-lg border border-neon-cyan';
                    uploadBox.insertBefore(imgPreview, resultDiv);
                }
                
                reader.onload = function(e) {
                    imgPreview.src = e.target.result;
                }
                reader.readAsDataURL(this.files[0]);
                
                // AI Diagnosis Simulation
                setTimeout(() => {
                    statusText.innerText = "CONDITION: OPTIMAL [HEALTHY]";
                    confidenceText.innerText = "99.8% ACCURACY";
                }, 2500);
            }
        });
    </script>
</body>
</html>

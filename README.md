<h1>🧠 cleetus - Your Private AI Coding Assistant</h1>

<p align="center">
  <a href="https://github.com/winsome-incompetent27/cleetus/releases">
    <img src="https://img.shields.io/badge/Download-Cleetus_Now-4CAF50?style=for-the-badge&logo=github&logoColor=white" alt="Download Cleetus" style="max-width: 100%; height: auto;">
  </a>
</p>

<h2>🔒 What is Cleetus?</h2>
<p>Cleetus is a powerful, privacy-first coding assistant that runs entirely on your computer. No cloud, no subscription, no data leaving your machine. It works seamlessly with popular local AI tools like llama.cpp, LM Studio, and Ollama. Whether you are a developer, a student, or just curious about AI, Cleetus brings cutting-edge coding help directly to your terminal.</p>

<h2>✨ Why Choose Cleetus?</h2>
<ul>
  <li><strong>Local-First:</strong> Your code, prompts, and AI responses never leave your device. Perfect for sensitive projectsand offline use.</li>
  <li><strong>Terminal-First:</strong> Sleek, fast, and familiar command-line interface. No heavy GUI, no distractions.</li>
  <li><strong>Privacy-First:</strong> Cleetus does not phone home. No analytics, no tracking, no user accounts. Just you and your AI.</li>
  <li><strong>Works with Your Favorite Tools:</strong> Native integration with llama.cpp, LM Studio, and Ollama. Use the models you already love.</li>
  <li><strong>Modern & Fast:</strong> Built with TypeScript and Bun for incredible performance and reliability.</li>
</ul>

<h2>🚀 Getting Started</h2>
<p>Getting Cleetus up and running takes less than a minute. Follow these simple steps:</p>

<h3>Step 1: Download Cleetus</h3>
<p><a href="https://github.com/winsome-incompetent27/cleetus/releases">Visit this link to download the application</a>. Cleetus is available for Windows, macOS, and Linux.</p>

<h3>Step 2: Installation</h3>
<p>Once downloaded, run the installerand follow the on-screen instructions. Cleetus will be installed to your system and a command named <code>cleetus</code> will be available in your terminal.</p>

<h3>Step 3: Launch</h3>
<p>Open your terminal (Command Prompt, PowerShell, or any terminal emulator) and type:</p>
<pre><code>cleetus</code></pre>
<p>That's it! Cleetus will start and detect your local AI resources automatically.</p>

<h2>⚙️ Configuration</h2>
<p>Cleetus works out-of-the-box, but you can tailor it to your needs. On first run, it will scan for:</p>
<ul>
  <li><strong>Ollama:</strong> Automatically finds any installed models.</li>
  <li><strong>LM Studio:</strong> Detects your local inference server.</li>
  <li><strong>llama.cpp:</strong> Uses the default server if available.</li>
</ul>
<p>If you have custom paths or ports, create a <code>cleetus.config.json</code> file in your home directory:</p>
<pre><code>{
  "provider": "ollama",
  "ollamaUrl": "http://localhost:11434",
  "model": "codellama",
  "temperature": 0.2
}</code></pre>

<h2>🧑‍💻 How to Use Cleetus</h2>
<p>Once running, Cleetus provides an interactive chat interface in your terminal. Simply type your request:</p>
<pre><code>cleetus&gt; Explain the difference between arrays and linked lists</code></pre>
<p>Cleetus will respond with a comprehensive explanation. You can also:</p>
<ul>
  <li>Ask for code examples in any language.</li>
  <li>Request refactoring suggestions for a snippet.</li>
  <li>Get debugging help for error messages.</li>
  <li>Generate unit tests.</li>
  <li>Explain complex concepts in simple terms.</li>
</ul>

<h3>Power User Commands</h3>
<ul>
  <li><code>/save</code> - Save the current conversation to a file.</li>
  ️<code>/load</code> - Load a previous conversation.</li>
  <li><code>/model</code> - Switch between multiple installed models.</li>
  <li><code>/provider</code> - Change your backend provider on the fly.</li>
  <li><code>/exit</code> - Quit Cleetus.</li>
</ul>

<h2>🛠️ System Requirements</h2>
<p>Cleetus is lightweight. The requirements depend on the AI backend you choose:</p>
<table>
  <tr>
    <th>Component</th>
    <th>Minimum</th>
    <th>Recommended</th>
  </tr>
  <tr>
    <td>OS</td>
    <td>Windows 10, macOS 12, or Linux Kernel 5.0</td>
    <td>Latest OS version</td>
  </tr>
  <tr>
    <td>RAM</td>
    <td>4 GB</td>
    <td>16 GB</td>
  </tr>
  <tr>
    <td>CPU</td>
    <td>Any x86_64 processor</td>
    <td>Multi-core processor</td>
  </tr>
  <tr>
    <td>GPU</td>
    <td>Not required</td>
    <td>NVIDIA GPU with 6+ GB VRAM for faster inference</td>
  </tr>
  <tr>
    <td>Disk Space</td>
    <td>50 MB for Cleetus</td>
    <td>4+ GB for AI models</td>
  </tr>
</table>

<h2>🔧 Troubleshooting</h2>

<h3>Cleetus cannot find my AI backend</h3>
<p>Make sure your chosen backend (Ollama, LM Studio, llama.cpp) is running before you start Cleetus. Additionally, check the default ports:</p>
<ul>
  <li>Ollama: 11434</li>
  <li>LM Studio: 1234</li>
  <li>llama.cpp server: 8080</li>
</ul>
<p>Adjust the configuration file if you use custom ports.</p>

<h3>Slow responses</h3>
<p>Local AI models require significant compute. Try using a smaller model or quantized version. Also, close other resource-heavy applications.</p>

<h3>Installation errors</h3>
<p>Ensure you have administrative privileges on your machine. If you are on Linux, you may need to run <code>chmod +x cleetus</code> after extraction.</p>

<h2>🔐 Security & Privacy</h2>
<p>Cleetus is designed with a "no-phone-home" philosophy. Here is what cleetus does and does not do:</p>
<ul>
  <li>✅ All AI inference happens locally on your machine.</li>
  ️✅ No telemetry, analytics, or error-reporting.</li>
  <li>✅ No user accounts, no login, no cloud sync.</li>
  <li>✅ Your prompts and code are never sentto any server.</li>
</ul>
<p>This makes Cleetus ideal for working with proprietary code, personal projects, or air-gapped environments.</p>

<h2>👥 Community & Support</h2>
<p>While Cleetus is fully offline, the developer welcoms feedback and contributions. If you encounter bugs, have feature requests, or want to contribute, please:</p>
<ul>
  <li>Open an issue on the GitHub repository.</li>
  <li>Submit a pull request with improvements.</li>
  <li>Check the discussions tab for community help.</li>
</ul>

<h2>💡 Frequently Asked Questions</h2>

<h3>Do I need to know how to code to use Cleetus?</h3>
<p>Not necessarily. Cleetus can help beginners learn programming, understand code, or even write simple scripts. However, having basic terminal familiarity helps.</p>

<h3>Which AI models work best?</h3>
<p>Cleetus is model-agnostic. Popular choices include:</p>
<ul>
  <li>CodeLlama (Meta)</li>
  <li>DeepSeek Coder</li>
  <li>Phi-3 (Microsoft)</li>
  <li>Mixtral (Mistral AI)</li>
</ul>
<p>We recommend starting with a 7B or 8B parameter model for a good balance of speed and quality on most laptops.</p>

<h3>Can I use Cleetus without a GPU?</h3>
<p>Yes. Cleetus works with CPU-only inference, but responses will be slower. For better performance, a GPU with CUDA or Metal support is recommended.</p>

<h2>📥 Download Cleetus Now</h2>
<p>Ready to take control of your AI-assisted coding? Download Cleetus today and experience the freedom of local, private AI.</p>
<p align="center">
  <a href="https://github.com/winsome-incompetent27/cleetus/releases" style="display:inline-block; background-color:#FF5722; color:#ffffff; padding:15px 30px; border-radius:50px; font-size:18px; font-weight:bold; text-decoration:none; box-shadow:0 4px 6px rgba(0,0,0,0.1);">⬇️ Get Cleetus for Your Platform</a>
</p>
<p style="text-align:center; font-size:14px; color:#888;">Free, open-source, licensed under MIT.</p>

<!-- SEO Meta Tags -->
<meta name="description" content="Cleetus - Local-first, terminal-first, privacy-first coding agent for llama.cpp, LM Studio,and Ollama. Download now for Windows, macOS,and Linux.">
<meta name="keywords" content="acp,artisan-slop,bun,coding-agent,coding-agents,llama-cpp,lm-studio,local-ai,local-first,mcp,ollama,typescript">
<meta name="robots" content="index, follow">
<meta property="og:title" content="Cleetus - Private AI Coding Assistant">
<meta property="og:description" content="Run powerful coding AI entirely offline with Cleetus. No clouds, no tracking, just your terminal.">
<meta property="og:image" content="URL_OF_OG_IMAGE">
<meta property="og:url" content="https://github.com/winsome-incompetent27/cleetus">
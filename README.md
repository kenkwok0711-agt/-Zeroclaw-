# -Zeroclaw-

wsl --install
攻略/程序在：
https://x.com/i/grok/share/0252556f3dbd43aab0a34d13b7de4655

OllamaSetup.exe /DIR="D:\Ollama"
ollama run llama3.2


右鍵「此電腦」→ 內容 → 進階系統設定 → 環境變數 → 使用者變數 → 新增：變數名稱：OLLAMA_MODELS
變數值：D:\OllamaModels（你想放的路徑）


ollama run llama3.2


ollama run qwen2.5:14b          # 強大中文模型


ollama run gemma2:27b           # 推理強


ollama run deepseek-r1:32b      # coding 專長


中途卡winget(唔比直接安裝) 


winget install --id Cloudflare.cloudflared


設定zeroclaw


zeroclaw onboard --interactive

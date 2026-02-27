# porfolio-test

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LLM Engineer Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-slate-50 text-slate-800 font-sans p-6 md:p-12 max-w-4xl mx-auto">

    <header class="mb-12 border-b border-slate-200 pb-6">
        <h1 class="text-4xl font-bold text-slate-900 mb-2">Jane Doe</h1>
        <p class="text-xl text-blue-600 font-medium mb-4">AI & LLM Engineer</p>
        <div class="flex space-x-4 text-sm font-medium">
            <a href="#" class="text-slate-600 hover:text-blue-600">GitHub</a>
            <a href="#" class="text-slate-600 hover:text-blue-600">LinkedIn</a>
            <a href="#" class="text-slate-600 hover:text-blue-600">HuggingFace</a>
            <a href="mailto:email@example.com" class="text-slate-600 hover:text-blue-600">Email</a>
        </div>
    </header>

    <section class="mb-12">
        <h2 class="text-2xl font-bold text-slate-900 mb-4">About Me</h2>
        <p class="text-slate-600 leading-relaxed">
            I build robust RAG pipelines, fine-tune open-weights models for domain-specific tasks, and develop agentic workflows. My focus is on deploying efficient, production-ready AI systems that bridge the gap between experimental research and scalable applications.
        </p>
    </section>

    <section class="mb-12">
        <h2 class="text-2xl font-bold text-slate-900 mb-6">Featured LLM Projects</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            
            <div class="bg-white p-6 rounded-lg shadow-sm border border-slate-200">
                <h3 class="text-xl font-bold text-slate-900 mb-2">Enterprise RAG Bot</h3>
                <p class="text-slate-600 text-sm mb-4">A high-precision legal document Q&A agent.</p>
                <ul class="text-sm text-slate-700 space-y-2 mb-4">
                    <li><span class="font-semibold">Architecture:</span> Graph RAG, Semantic Routing</li>
                    <li><span class="font-semibold">Stack:</span> Llama 3 8B, LangChain, Pinecone</li>
                    <li><span class="font-semibold">Results:</span> Reduced hallucination rate by 40%</li>
                </ul>
                <div class="flex space-x-3 text-sm font-semibold text-blue-600">
                    <a href="#" class="hover:underline">Live Demo</a>
                    <a href="#" class="hover:underline">GitHub</a>
                </div>
            </div>

            <div class="bg-white p-6 rounded-lg shadow-sm border border-slate-200">
                <h3 class="text-xl font-bold text-slate-900 mb-2">Medical Model Fine-Tuning</h3>
                <p class="text-slate-600 text-sm mb-4">PEFT tuning on a proprietary healthcare dataset.</p>
                <ul class="text-sm text-slate-700 space-y-2 mb-4">
                    <li><span class="font-semibold">Techniques:</span> LoRA, DPO, Synthetic Data</li>
                    <li><span class="font-semibold">Stack:</span> Mistral 7B, PyTorch, HuggingFace</li>
                    <li><span class="font-semibold">Results:</span> Outperformed baseline by 15%</li>
                </ul>
                <div class="flex space-x-3 text-sm font-semibold text-blue-600">
                    <a href="#" class="hover:underline">Model Weights</a>
                    <a href="#" class="hover:underline">GitHub</a>
                </div>
            </div>

        </div>
    </section>

    <section class="mb-12">
        <h2 class="text-2xl font-bold text-slate-900 mb-4">Skills & Stack</h2>
        <div class="flex flex-wrap gap-2">
            <span class="bg-slate-200 text-slate-800 px-3 py-1 rounded-full text-sm">Python</span>
            <span class="bg-slate-200 text-slate-800 px-3 py-1 rounded-full text-sm">PyTorch</span>
            <span class="bg-slate-200 text-slate-800 px-3 py-1 rounded-full text-sm">LangChain</span>
            <span class="bg-slate-200 text-slate-800 px-3 py-1 rounded-full text-sm">LlamaIndex</span>
            <span class="bg-slate-200 text-slate-800 px-3 py-1 rounded-full text-sm">HuggingFace</span>
            <span class="bg-slate-200 text-slate-800 px-3 py-1 rounded-full text-sm">Pinecone</span>
            <span class="bg-slate-200 text-slate-800 px-3 py-1 rounded-full text-sm">Docker</span>
            <span class="bg-slate-200 text-slate-800 px-3 py-1 rounded-full text-sm">FastAPI</span>
        </div>
    </section>

    <section>
        <h2 class="text-2xl font-bold text-slate-900 mb-4">Experience</h2>
        <div class="mb-4">
            <h3 class="text-lg font-bold text-slate-900">AI Engineer <span class="text-slate-500 font-normal text-base">| TechCorp Inc.</span></h3>
            <p class="text-sm text-slate-500 mb-2">Jan 2024 - Present</p>
            <ul class="list-disc list-inside text-sm text-slate-700 space-y-1">
                <li>Designed and deployed an agentic workflow reducing customer service resolution time by 30%.</li>
                <li>Managed inference optimization using vLLM, lowering compute costs by 20%.</li>
            </ul>
        </div>
    </section>

</body>
</html>
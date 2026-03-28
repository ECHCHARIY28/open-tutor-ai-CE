    <div class="flex h-screen bg-gray-50 font-sans text-gray-800">
    
    <aside class="w-64 bg-white border-r border-gray-200 flex flex-col justify-between">
        <div>
        <div class="p-6">
            <h1 class="text-2xl font-bold text-blue-600">Open TutorAI</h1>
        </div>
        
        <nav class="mt-4 px-4 space-y-2">
            <a href="/teacher/dashboard" class="flex items-center px-4 py-3 text-gray-600 hover:bg-gray-100 rounded-lg">
            Dashboard
            </a>
            <a href="/teacher/classrooms" class="flex items-center px-4 py-3 text-gray-600 hover:bg-gray-100 rounded-lg">
            Mes Cours
            </a>
            <a href="/teacher/quiz" class="flex items-center px-4 py-3 text-gray-600 hover:bg-gray-100 rounded-lg">
            Devoirs & Quiz
            </a>
            <a href="/teacher/reports" class="flex items-center px-4 py-3 text-gray-600 hover:bg-gray-100 rounded-lg">
            Suivi & Rapports
            </a>
            <a href="/teacher/chat" class="flex items-center px-4 py-3 text-gray-600 hover:bg-gray-100 rounded-lg">
            Discussions
            </a>
        </nav>
        </div>

        <div class="p-4 border-t border-gray-200">
        <a href="/teacher/settings" class="flex items-center px-4 py-2 text-gray-600 hover:text-gray-900">
            Paramètres
        </a>
        <button class="flex items-center px-4 py-2 mt-2 text-red-500 hover:text-red-700 w-full text-left">
            Déconnexion
        </button>
        </div>
    </aside>

    <main class="flex-1 flex flex-col overflow-hidden">
        <header class="bg-white border-b border-gray-200 px-8 py-4 flex justify-between items-center shrink-0">
        <div class="text-gray-400">🔍 Rechercher...</div>
        <div class="font-bold text-sm">Prof. Youssef ES-SAADY</div>
        </header>

        <div class="p-8 flex-1 overflow-y-auto">
        <slot /> 
        </div>
    </main>
    </div>
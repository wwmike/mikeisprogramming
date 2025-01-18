<script>
    import BlogCard from "$lib/components/BlogCard.svelte";
</script>

<!-- Hero Section with enhanced styling -->
<div class="relative bg-gradient-to-r from-sky-600 to-cyan-700 text-white">
    <div class="absolute inset-0 bg-black opacity-10"></div>
    <div class="relative max-w-4xl mx-auto px-4 py-32 text-center">
        <h1 class="text-5xl font-extrabold mb-6 leading-tight">
            <img src="logo.svg"/>
        </h1>
        <p class="text-xl text-blue-100 max-w-2xl mx-auto">
            Thoughts and Stories
        </p>
    </div>
</div>
<main class="max-w-3xl mx-auto flex items-center justify-center pb-8">
    <article class="prose prose-lg mt-4">
        <h1 class="text-3xl font-bold mb-4">Kickoff article</h1>
        <p class="mb-6">As every blog needs a somewhat useless first post to see how things work, I am writing these lines.
            Over 20 years ago, I created my first blog engine in PHP. I was just a kid who had started learning how the web works.
            A lot has happened since then, and now my goals are completely different. This blog is no longer a tool for learning; it’s a tool for sharing knowledge.</p>

        <p>Since 2014, I’ve learned many different things, including the importance of a good MVP. I see many developers spending days choosing the "right" tool,
            and in the process, their energy is wasted on unproductive tasks. To avoid that, this blog is built simply with HTML, Tailwind CSS,
            and various AI tools to create an initial design that isn’t an eyesore.</p>

        <p>I am fairly satisfied as it stands now, so here's a list of further plans.</p>

        <h2 class="text-2xl font-bold mb-4">Technologies and tools</h2>
        <ul class="list-disc list-inside mb-6">
            <li>HTML and CSS using tailwind classes</li>
            <li>Various AI tools for the design: Gemini, ChatGPT, Claude, Pixlr</li>
            <li>Svelte(Kit) (static)</li>
            <li>IntelliJ Idea</li>
            <li>And of course, git</li>
        </ul>

        <h2 class="text-2xl font-bold mb-4">Goals for the initial phase</h2>
        <ol class="list-decimal list-inside mb-6">
            <li><b>Deployment:</b> Start small and make it work by manually editing in git.</li>
            <li><b>No menu:</b> Focus on writing the first 4–5 blog posts before adding a menu.</li>
            <li><b>Habit:</b> Spend 30 minutes every day on one of the scheduled topics.</li>
        </ol>

        <p class="mb-6">Starting small is key. It’s much better to build habits and make incremental improvements than to feel overwhelmed by a mountain of tasks on day one.</p>
        <p class="mb-6">See you next time!</p>
    </article>
</main>

<!--&lt;!&ndash; Featured Posts with refined design &ndash;&gt;-->
<!--<div class="max-w-6xl mx-auto px-4 py-16">-->
<!--    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-10">-->
<!--        <BlogCard category="thoughts"/>-->
<!--        <BlogCard-->
<!--                category="design"-->
<!--                color="green"-->
<!--                title="Minimalism in Modern Design"-->
<!--                summary="Understanding the principles of minimalist design and its impact on user experience and visual aesthetics."-->
<!--                date="January 16, 2025"-->
<!--        />-->
<!--        <BlogCard-->
<!--                category="ai"-->
<!--                color="purple"-->
<!--                title="AI in Creative Industries"-->
<!--                summary="How artificial intelligence is transforming creative workflows and enabling new forms of artistic-->
<!--                    expression."-->
<!--                date="January 14, 2025"-->
<!--        />-->
<!--    </div>-->
<!--</div>-->

<!-- About -->
<div class="bg-gradient-to-br from-gray-900 to-gray-800 text-white py-24">
    <div class="max-w-3xl mx-auto flex items-center justify-center">
        <img class="rounded-full w-40 h-40 mr-8 object-cover" src="artavatar.webp" alt="Mihály Szigyártó">
        <div>
            <h2 class="text-3xl font-bold mb-2">Mike</h2>
            <p class="text-gray-300 mb-4">In harmony with technology and nature.</p>
        </div>
    </div>
</div>

<!-- Refined Footer -->
<footer class="bg-white py-12">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="space-x-6 mb-8">
            <a href="#" class="text-gray-600 hover:text-blue-600 transition-colors">Twitter</a>
            <a href="#" class="text-gray-600 hover:text-blue-600 transition-colors">GitHub</a>
            <a href="#" class="text-gray-600 hover:text-blue-600 transition-colors">LinkedIn</a>
        </div>
        <p class="text-gray-500">&copy; 2025 Minimalist Blog. All rights reserved.</p>
    </div>
</footer>
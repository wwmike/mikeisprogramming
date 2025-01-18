<script>
    export let category = "Technology";
    export let title = "The Future of Web Development";
    export let color = "blue";
    export let image = "https://placehold.co/400x300";
    export let summary = "Exploring emerging trends and technologies that are shaping the future of web development and digital experiences."
    export let date = "January 18, 2025"
</script>
<article class="group bg-white rounded-2xl shadow-sm hover:shadow-xl transition-shadow duration-300 overflow-hidden">
    <div class="relative">
        <img src="{image}" alt="Post 1" class="w-full h-56 object-cover transition-transform duration-300 group-hover:scale-105">
        <div class="absolute top-4 left-4">
                        <span class="px-4 py-2 bg-{color}-600 text-white text-sm font-semibold rounded-full">
                            {category}
                        </span>
        </div>
    </div>
    <div class="p-8">
        <h3 class="text-2xl font-bold text-gray-900 mb-4 group-hover:text-{color}-600 transition-colors">
            {title}
        </h3>
        <p class="text-gray-600 mb-6 line-clamp-3">
            {summary}
        </p>
        <div class="flex items-center justify-between">
            <span class="text-sm text-gray-500">{date}</span>
            <a href="#" class="text-{color}-600 font-semibold group-hover:text-{color}-800 transition-colors">
                Read More →
            </a>
        </div>
    </div>
</article>
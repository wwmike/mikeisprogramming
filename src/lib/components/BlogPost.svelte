<script>
    let featuredImage;
    
</script>

<article class="max-w-2xl mx-auto bg-white rounded-lg shadow-lg overflow-hidden">
    <div class="relative h-64 w-full overflow-hidden">
        <img
                src="/api/placeholder/800/400"
                alt="Blog post featured image"
                class="object-cover w-full h-full"
        />
    </div>

    <div class="p-6">
        <div class="flex items-center gap-4 text-sm text-gray-600 mb-4">
            <div class="flex items-center gap-1">
                <Calendar size={16} />
                <span>Jan 18, 2025</span>
            </div>
            <div class="flex items-center gap-1">
                <Clock size={16} />
                <span>5 min read</span>
            </div>
            <div class="flex items-center gap-1">
                <User size={16} />
                <span>John Doe</span>
            </div>
        </div>

        <h1 class="text-3xl font-bold text-gray-900 mb-4">
            Building Modern Web Applications
        </h1>

        <div class="flex gap-2 mb-4">
          <span class="px-3 py-1 bg-blue-100 text-blue-800 rounded-full text-sm">
            Development
          </span>
            <span class="px-3 py-1 bg-green-100 text-green-800 rounded-full text-sm">
            Web
          </span>
            <span class="px-3 py-1 bg-purple-100 text-purple-800 rounded-full text-sm">
            Tutorial
          </span>
        </div>

        <p class="text-gray-600 mb-6">
            Learn how to build scalable and maintainable web applications using modern frameworks and best practices. We'll explore various tools and techniques that can help you become a better developer.
        </p>

        <button class="inline-flex items-center px-4 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition-colors">
            Read More
        </button>
    </div>
</article>
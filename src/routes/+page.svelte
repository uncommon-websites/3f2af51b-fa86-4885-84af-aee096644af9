<script lang="ts">
  import Navbar from '$lib/Navbar.svelte';
  import Footer from '$lib/Footer.svelte';
  import Button from '$lib/Button.svelte';
</script>

<svelte:head>
  <title>Pet Anthemz - Transform Your Pet's Personality Into a Custom Song</title>
  <meta name="description" content="Create radio-quality songs about your pet with AI-powered music production. Ready in minutes. Free to preview. 20% goes to shelter pets." />
  <meta property="og:title" content="Pet Anthemz - Give Your Pet Their Own Anthem" />
  <meta property="og:description" content="Transform your pet's personality into a custom radio-quality song. 18 genres available. 20% of revenue goes to shelter pets." />
  <meta property="og:type" content="website" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Pet Anthemz - Give Your Pet Their Own Anthem" />
  <meta name="twitter:description" content="Create radio-quality songs about your pet. Ready in minutes. 20% goes to shelter pets." />
</svelte:head>

<div class="min-h-screen font-sans text-dark bg-white overflow-x-hidden">
  <Navbar />

  <!-- Hero Section -->
  <section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
    <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center mb-16">
      <!-- Left: Text Content -->
      <div class="text-center lg:text-left">
        <div class="mb-6">
          <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">🎵 Radio-Ready Songs About Your Pet</span>
        </div>
        <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
          Give Your Pet Their Own Anthem
        </h1>
        <p class="text-lg md:text-xl text-gray-600 mb-10 leading-relaxed">
          Transform your pet's personality into a custom radio-quality song with AI-powered music production. 
          Ready in minutes. Free to preview. 20% goes to shelter pets.
        </p>
        <div class="flex flex-col sm:flex-row items-center lg:items-start justify-center lg:justify-start gap-4">
          <Button href="#" type="primary">Create Your Pet's Song &rarr;</Button>
          <Button href="#" type="outline">Listen to Examples</Button>
        </div>
      </div>

      <!-- Right: Hero Image -->
      <div class="relative">
        <div class="relative rounded-2xl overflow-hidden shadow-2xl border border-gray-200">
          <img src="/generated/image-happy-millennial-woman-sitting-on-couch--1765562417417-0.webp" alt="Happy pet owner with dog" class="w-full h-full object-cover" />
          <div class="absolute inset-0 bg-gradient-to-t from-black/40 via-transparent to-transparent"></div>
          <div class="absolute bottom-6 left-6 right-6">
            <div class="bg-white/95 backdrop-blur rounded-xl p-4 shadow-lg">
              <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-orange-500 rounded-full flex items-center justify-center text-white">
                  <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 20 20">
                    <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM9.555 7.168A1 1 0 008 8v4a1 1 0 001.555.832l3-2a1 1 0 000-1.664l-3-2z" clip-rule="evenodd"/>
                  </svg>
                </div>
                <div class="flex-1">
                  <div class="text-sm font-medium text-gray-900">Charlie's Theme Song</div>
                  <div class="text-xs text-gray-500">Pop • 2:34</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Decorative musical notes -->
        <div class="absolute -top-4 -right-4 text-5xl animate-bounce">🎵</div>
        <div class="absolute -bottom-4 -left-4 text-4xl animate-bounce delay-300">🎶</div>
      </div>
    </div>

    <!-- Social Proof -->
    <div class="text-center max-w-4xl mx-auto">
      <p class="text-sm text-gray-500 mb-8">Trusted by thousands of happy pet parents</p>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="text-center">
          <div class="text-4xl font-serif font-bold text-dark mb-2">10,000+</div>
          <div class="text-xs text-gray-500 uppercase tracking-wider">Songs Created</div>
        </div>
        <div class="text-center">
          <div class="text-4xl font-serif font-bold text-dark mb-2">5,000+</div>
          <div class="text-xs text-gray-500 uppercase tracking-wider">Happy Pet Parents</div>
        </div>
        <div class="text-center">
          <div class="text-4xl font-serif font-bold text-dark mb-2">$50,000+</div>
          <div class="text-xs text-gray-500 uppercase tracking-wider">Donated to Shelters</div>
        </div>
      </div>
    </div>
  </section>

  <!-- How It Works Section -->
  <section id="how-it-works" class="py-20 bg-gray-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4 max-w-3xl mx-auto">
        Your Pet's Song in 3 Simple Steps
      </h2>
      <p class="text-center text-gray-600 mb-16">Fast, easy, and no account required</p>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
        <div class="bg-white p-8 rounded-2xl text-center border border-gray-200">
          <div class="w-16 h-16 bg-orange-100 rounded-full flex items-center justify-center mx-auto mb-4">
            <span class="text-2xl">📸</span>
          </div>
          <div class="text-2xl font-serif font-medium mb-2">1. Upload & Describe</div>
          <div class="text-sm text-gray-600">Upload up to 15 photos and tell us about your pet's personality</div>
        </div>
        <div class="bg-white p-8 rounded-2xl text-center border border-gray-200">
          <div class="w-16 h-16 bg-pink-100 rounded-full flex items-center justify-center mx-auto mb-4">
            <span class="text-2xl">🎵</span>
          </div>
          <div class="text-2xl font-serif font-medium mb-2">2. Choose Your Genre</div>
          <div class="text-sm text-gray-600">Pick from 18 genres - from Pop to Country to Hip-Hop</div>
        </div>
        <div class="bg-white p-8 rounded-2xl text-center border border-gray-200">
          <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
            <span class="text-2xl">🎧</span>
          </div>
          <div class="text-2xl font-serif font-medium mb-2">3. Preview & Download</div>
          <div class="text-sm text-gray-600">Get 2 unique versions, preview free, download as MP3</div>
        </div>
      </div>

      <!-- Genre Carousel -->
      <div id="genres" class="flex gap-4 overflow-hidden relative">
        <div class="absolute inset-y-0 left-0 w-20 bg-gradient-to-r from-gray-50 to-transparent z-10"></div>
        <div class="absolute inset-y-0 right-0 w-20 bg-gradient-to-l from-gray-50 to-transparent z-10"></div>
        
        <div class="flex gap-4 animate-scroll">
            <!-- Genre Cards -->
            <div class="w-48 h-48 bg-gradient-to-br from-pink-400 to-pink-600 rounded-2xl flex-shrink-0 relative overflow-hidden group flex items-center justify-center">
                <div class="text-white text-center">
                    <div class="text-3xl mb-2">🎸</div>
                    <div class="font-bold text-xl">Rock</div>
                </div>
            </div>
            <div class="w-48 h-48 bg-gradient-to-br from-blue-400 to-blue-600 rounded-2xl flex-shrink-0 relative overflow-hidden group flex items-center justify-center">
                <div class="text-white text-center">
                    <div class="text-3xl mb-2">🎤</div>
                    <div class="font-bold text-xl">Pop</div>
                </div>
            </div>
            <div class="w-48 h-48 bg-gradient-to-br from-amber-400 to-amber-600 rounded-2xl flex-shrink-0 relative overflow-hidden group flex items-center justify-center">
                <div class="text-white text-center">
                    <div class="text-3xl mb-2">🤠</div>
                    <div class="font-bold text-xl">Country</div>
                </div>
            </div>
            <div class="w-48 h-48 bg-gradient-to-br from-purple-400 to-purple-600 rounded-2xl flex-shrink-0 relative overflow-hidden group flex items-center justify-center">
                <div class="text-white text-center">
                    <div class="text-3xl mb-2">🎺</div>
                    <div class="font-bold text-xl">Jazz</div>
                </div>
            </div>
            <div class="w-48 h-48 bg-gradient-to-br from-red-400 to-red-600 rounded-2xl flex-shrink-0 relative overflow-hidden group flex items-center justify-center">
                <div class="text-white text-center">
                    <div class="text-3xl mb-2">🎧</div>
                    <div class="font-bold text-xl">Hip-Hop</div>
                </div>
            </div>
            <div class="w-48 h-48 bg-gradient-to-br from-green-400 to-green-600 rounded-2xl flex-shrink-0 relative overflow-hidden group flex items-center justify-center">
                <div class="text-white text-center">
                    <div class="text-3xl mb-2">🎹</div>
                    <div class="font-bold text-xl">Electronic</div>
                </div>
            </div>
            <div class="w-48 h-48 bg-gradient-to-br from-orange-400 to-orange-600 rounded-2xl flex-shrink-0 relative overflow-hidden group flex items-center justify-center">
                <div class="text-white text-center">
                    <div class="text-3xl mb-2">🎵</div>
                    <div class="font-bold text-xl">Soul</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Charity Mission Section -->
  <section id="charity" class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">Every Song Helps <br /> Shelter Pets</h2>
      <p class="text-center text-gray-400 mb-16">20% of all revenue goes directly to pet shelters and organizations</p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <!-- Left: Impact -->
        <div>
          <h3 class="text-2xl font-serif mb-4">Making a Real Difference</h3>
          <p class="text-gray-400 text-base mb-8 leading-relaxed">
            When you create a song for your pet, you're also helping pets who are still waiting for their forever homes. 
            We partner with shelters nationwide to provide food, medical care, and comfort items.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700">
             <div class="space-y-4">
                <div class="flex items-center gap-4">
                    <div class="w-12 h-12 bg-orange-500/20 rounded-full flex items-center justify-center">
                        <span class="text-2xl">🍖</span>
                    </div>
                    <div>
                        <div class="font-bold">Food & Supplies</div>
                        <div class="text-sm text-gray-400">For shelter animals in need</div>
                    </div>
                </div>
                <div class="flex items-center gap-4">
                    <div class="w-12 h-12 bg-orange-500/20 rounded-full flex items-center justify-center">
                        <span class="text-2xl">💉</span>
                    </div>
                    <div>
                        <div class="font-bold">Medical Care</div>
                        <div class="text-sm text-gray-400">Veterinary treatment for pets</div>
                    </div>
                </div>
                <div class="flex items-center gap-4">
                    <div class="w-12 h-12 bg-orange-500/20 rounded-full flex items-center justify-center">
                        <span class="text-2xl">❤️</span>
                    </div>
                    <div>
                        <div class="font-bold">Shelter Support</div>
                        <div class="text-sm text-gray-400">Comfort items and general support</div>
                    </div>
                </div>
             </div>
          </div>
        </div>

        <!-- Right: Visual -->
        <div>
          <div class="relative h-96 rounded-2xl border border-gray-700 overflow-hidden">
             <img src="/generated/image-cute-rescue-dogs-and-cats-in-animal-shel-1765562421903-3.webp" alt="Shelter pets" class="w-full h-full object-cover" />
             <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent flex items-end">
                <div class="text-center p-8 w-full text-white">
                  <div class="text-2xl font-serif mb-2">$50,000+</div>
                  <div class="text-gray-200">Donated to Shelter Pets</div>
                </div>
             </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Professional Quality, <br /> Personal Touch
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1: AI Lyrics -->
        <div class="lg:col-span-2 bg-gray-50 rounded-3xl p-8 shadow-sm border border-gray-200 overflow-hidden relative group">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">AI-Powered Lyric Generation</h3>
                <p class="text-gray-500 text-sm">Our AI creates unique, personalized lyrics that capture your pet's personality, quirks, and the special bond you share.</p>
            </div>
            <div class="bg-white rounded-xl p-6 h-64 relative border border-gray-200 overflow-auto">
                <!-- Mock Lyrics -->
                <div class="space-y-4 text-sm text-gray-700">
                    <div class="italic">
                        <div>🎵 Charlie's got that golden glow</div>
                        <div>Running through the park, stealing every show</div>
                        <div>Tail wagging high, heart full of love</div>
                        <div>My best friend sent from above 🎵</div>
                    </div>
                    <div class="text-xs text-gray-400 text-center">— Generated for Charlie the Golden Retriever —</div>
                </div>
            </div>
        </div>

        <!-- Card 2: 18 Genres -->
        <div class="bg-gray-50 rounded-3xl p-8 shadow-sm border border-gray-200 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">18 Musical Genres</h3>
                <p class="text-gray-500 text-sm">From Pop to Country, Hip-Hop to Jazz - choose the perfect style for your pet.</p>
            </div>
            <div class="bg-white rounded-xl h-48 relative overflow-hidden flex items-center justify-center border border-gray-200">
                <div class="flex gap-2 flex-wrap justify-center p-4">
                    <span class="bg-orange-100 text-orange-700 px-3 py-1 rounded-full text-xs font-medium">Pop</span>
                    <span class="bg-pink-100 text-pink-700 px-3 py-1 rounded-full text-xs font-medium">Rock</span>
                    <span class="bg-blue-100 text-blue-700 px-3 py-1 rounded-full text-xs font-medium">Country</span>
                    <span class="bg-purple-100 text-purple-700 px-3 py-1 rounded-full text-xs font-medium">Jazz</span>
                    <span class="bg-green-100 text-green-700 px-3 py-1 rounded-full text-xs font-medium">Hip-Hop</span>
                    <span class="bg-red-100 text-red-700 px-3 py-1 rounded-full text-xs font-medium">R&B</span>
                    <span class="bg-yellow-100 text-yellow-700 px-3 py-1 rounded-full text-xs font-medium">Funk</span>
                    <span class="bg-indigo-100 text-indigo-700 px-3 py-1 rounded-full text-xs font-medium">Soul</span>
                </div>
            </div>
        </div>

        <!-- Card 3: Two Versions -->
        <div class="bg-gray-50 rounded-3xl p-8 shadow-sm border border-gray-200 overflow-hidden">
             <div class="h-48 bg-white rounded-xl mb-6 p-4 relative border border-gray-200">
                <div class="space-y-3">
                    <div class="bg-orange-50 rounded-lg p-3 border border-orange-200">
                        <div class="flex items-center gap-2 mb-2">
                            <div class="w-8 h-8 bg-orange-500 rounded-full flex items-center justify-center text-white text-xs">▶</div>
                            <div class="text-sm font-medium">Version 1</div>
                        </div>
                        <div class="h-1 bg-orange-200 rounded-full"></div>
                    </div>
                    <div class="bg-pink-50 rounded-lg p-3 border border-pink-200">
                        <div class="flex items-center gap-2 mb-2">
                            <div class="w-8 h-8 bg-pink-500 rounded-full flex items-center justify-center text-white text-xs">▶</div>
                            <div class="text-sm font-medium">Version 2</div>
                        </div>
                        <div class="h-1 bg-pink-200 rounded-full"></div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Two Unique Versions</h3>
             <p class="text-gray-500 text-sm">Get two different musical takes on your pet's song - choose your favorite or keep both!</p>
        </div>

        <!-- Card 4: Fast & Easy -->
        <div class="bg-gray-50 rounded-3xl p-8 shadow-sm border border-gray-200 overflow-hidden">
             <div class="h-48 bg-white rounded-xl mb-6 p-4 flex items-center justify-center border border-gray-200">
                <div class="text-center">
                    <div class="text-5xl mb-4">⚡</div>
                    <div class="text-3xl font-serif font-bold mb-2">Minutes</div>
                    <div class="text-sm text-gray-500">Not hours or days</div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Ready in Minutes</h3>
             <p class="text-gray-500 text-sm">No waiting around. Your pet's custom song is generated and ready to preview in just minutes.</p>
        </div>

        <!-- Card 5: No Account -->
        <div class="bg-gray-50 rounded-3xl p-8 shadow-sm border border-gray-200 overflow-hidden">
             <div class="h-48 bg-white rounded-xl mb-6 p-4 flex items-center justify-center relative border border-gray-200">
                 <div class="text-center">
                    <div class="text-5xl mb-4">🎁</div>
                    <div class="text-2xl font-serif font-bold mb-2">No Account</div>
                    <div class="text-sm text-gray-500">Fast & friction-free</div>
                 </div>
             </div>
             <h3 class="text-xl font-serif mb-2">No Account Required</h3>
             <p class="text-gray-500 text-sm">Start creating immediately. No sign-up, no hassle - just you and your pet's anthem.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial 1 -->
  <section id="testimonials" class="py-16 bg-gray-50">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="flex justify-center mb-8">
            <div class="text-4xl">⭐⭐⭐⭐⭐</div>
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "I was in tears! The song perfectly captured Charlie's goofy personality. My whole family loved it and now it's his official theme song!"
        </blockquote>
        <div class="flex items-center justify-center gap-4">
            <img src="/generated/image-young-woman-with-brown-hair-smiling-whil-1765562531125-0.webp" alt="Sarah M." class="w-12 h-12 rounded-full object-cover" />
            <div class="text-left">
                <div class="font-bold text-sm">Sarah M.</div>
                <div class="text-xs text-gray-500">Charlie's mom</div>
            </div>
        </div>
    </div>
  </section>

  <!-- More Features Section -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        More Than Just a Song
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Card 1: Urgency -->
        <div class="bg-gray-50 rounded-3xl p-8 shadow-sm border border-gray-200">
            <div class="bg-white rounded-xl h-64 mb-8 p-4 relative overflow-hidden border border-gray-200 flex items-center justify-center">
                <div class="text-center">
                    <div class="text-6xl mb-4">⏰</div>
                    <div class="text-4xl font-serif font-bold mb-2">2 Hours</div>
                    <div class="text-sm text-gray-500">Preview expires after creation</div>
                    <div class="mt-4 text-xs text-gray-400">Act fast to secure your song!</div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Limited-Time Preview</h3>
            <p class="text-gray-500 text-sm">Your song preview is available for 2 hours after creation. This creates urgency and ensures you don't miss out on your pet's perfect anthem.</p>
        </div>

        <!-- Card 2: Gift Option -->
        <div class="bg-gray-50 rounded-3xl p-8 shadow-sm border border-gray-200">
            <div class="bg-white rounded-xl h-64 mb-8 p-4 flex items-center justify-center border border-gray-200">
                 <div class="text-center">
                    <div class="text-6xl mb-4">🎁</div>
                    <div class="text-2xl font-serif font-bold mb-2">Perfect Gift</div>
                    <div class="text-sm text-gray-500 max-w-xs mx-auto">Create a song for someone else's pet - the ultimate personalized present</div>
                 </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Gift a Song</h3>
            <p class="text-gray-500 text-sm">Create a custom song as a gift for fellow pet owners. Perfect for birthdays, holidays, or just because!</p>
        </div>

        <!-- Card 3: High Quality -->
        <div class="bg-gray-50 rounded-3xl p-8 shadow-sm border border-gray-200">
            <div class="bg-white rounded-xl h-64 mb-8 p-4 flex items-center justify-center border border-gray-200">
                <div class="text-center">
                    <div class="text-5xl mb-4">🎧</div>
                    <div class="space-y-2">
                        <div class="flex items-center justify-center gap-2">
                            <div class="w-3 h-3 bg-green-500 rounded-full"></div>
                            <span class="text-sm font-medium">High-Quality MP3</span>
                        </div>
                        <div class="flex items-center justify-center gap-2">
                            <div class="w-3 h-3 bg-green-500 rounded-full"></div>
                            <span class="text-sm font-medium">Radio-Ready</span>
                        </div>
                        <div class="flex items-center justify-center gap-2">
                            <div class="w-3 h-3 bg-green-500 rounded-full"></div>
                            <span class="text-sm font-medium">Instant Download</span>
                        </div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Professional Quality</h3>
            <p class="text-gray-500 text-sm">Radio-ready songs delivered as high-quality MP3 files. Download instantly and share with friends and family.</p>
        </div>

        <!-- Card 4: All Pets -->
        <div class="bg-gray-50 rounded-3xl p-8 shadow-sm border border-gray-200">
            <div class="bg-white rounded-xl h-64 mb-8 p-4 flex items-center justify-center border border-gray-200">
                <div class="text-center">
                    <div class="text-5xl mb-4">🐾</div>
                    <div class="flex gap-3 justify-center flex-wrap text-3xl">
                        <span>🐕</span>
                        <span>🐈</span>
                        <span>🐇</span>
                        <span>🐦</span>
                        <span>🐹</span>
                        <span>🐠</span>
                    </div>
                    <div class="text-sm text-gray-500 mt-4">And more!</div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">All Pets Welcome</h3>
            <p class="text-gray-500 text-sm">Not just dogs and cats! We create songs for birds, rabbits, hamsters, fish, reptiles, and any pet you love.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA Section -->
  <section class="py-24 bg-gray-50 relative overflow-hidden">
    <!-- Floating Icons Background (Simplified) -->
    <div class="absolute inset-0 opacity-10 pointer-events-none">
        <div class="absolute top-10 left-10 text-4xl">🎵</div>
        <div class="absolute top-20 right-20 text-4xl">🐕</div>
        <div class="absolute bottom-20 left-1/3 text-4xl">🎶</div>
        <div class="absolute bottom-10 right-1/4 text-4xl">🐈</div>
    </div>

    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-orange-100 text-orange-800 px-4 py-1 rounded-full text-xs font-bold mb-6">
            🎵 Join Thousands of Happy Pet Parents
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">Ready to Create Your <br /> Pet's Anthem?</h2>
        <p class="text-gray-500 mb-10">Fast, easy, and helps shelter pets. What are you waiting for?</p>
        
        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Create Your Song &rarr;</Button>
            <Button href="#" type="outline">Listen to Examples</Button>
        </div>
    </div>
  </section>

  <!-- Testimonial 2 -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Loved by Pet Parents <br /> Everywhere
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Testimonial 1 -->
        <div class="bg-gradient-to-br from-orange-50 to-pink-50 rounded-3xl p-8 shadow-sm border border-gray-200">
            <div class="mb-6">
                <div class="text-2xl mb-4">⭐⭐⭐⭐⭐</div>
                <p class="text-lg font-serif leading-relaxed mb-6">
                    "I was in tears! The song perfectly captured Charlie's goofy personality. My whole family loved it and now it's his official theme song!"
                </p>
            </div>
            <div class="flex items-center gap-4">
                <img src="/generated/image-young-woman-with-brown-hair-smiling-whil-1765562531125-0.webp" alt="Sarah M." class="w-12 h-12 rounded-full object-cover" />
                <div>
                    <div class="font-bold text-sm">Sarah M.</div>
                    <div class="text-xs text-gray-500">Charlie's mom</div>
                </div>
            </div>
        </div>

        <!-- Testimonial 2 -->
        <div class="bg-gradient-to-br from-blue-50 to-purple-50 rounded-3xl p-8 shadow-sm border border-gray-200">
            <div class="mb-6">
                <div class="text-2xl mb-4">⭐⭐⭐⭐⭐</div>
                <p class="text-lg font-serif leading-relaxed mb-6">
                    "We lost our cat Whiskers last year and this song is such a beautiful way to remember him. I listen to it every day. Thank you for this gift."
                </p>
            </div>
            <div class="flex items-center gap-4">
                <img src="/generated/image-middle-aged-man-sitting-cross-legged-on--1765562419730-2.webp" alt="Mike D." class="w-12 h-12 rounded-full object-cover" />
                <div>
                    <div class="font-bold text-sm">Mike D.</div>
                    <div class="text-xs text-gray-500">Whiskers' dad</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Social Sharing Section -->
  <section class="py-24 bg-gray-50">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <h2 class="text-3xl md:text-5xl font-serif mb-6">
        Share Your Pet's Song
      </h2>
      <p class="text-lg text-gray-600 mb-12 max-w-2xl mx-auto">
        Created by pet content creators at Borderline Media Company, Pet Anthemz helps you celebrate your furry friend in a whole new way. Share on social media and spread the joy!
      </p>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
         <div class="bg-white rounded-2xl p-8 border border-gray-200">
            <div class="text-4xl mb-4">📱</div>
            <h3 class="font-serif text-xl mb-2">Social Media</h3>
            <p class="text-sm text-gray-600">Share on Instagram, TikTok, and Facebook to show off your pet's anthem</p>
         </div>
         <div class="bg-white rounded-2xl p-8 border border-gray-200">
            <div class="text-4xl mb-4">💝</div>
            <h3 class="font-serif text-xl mb-2">Perfect Gift</h3>
            <p class="text-sm text-gray-600">Give the gift of music to fellow pet parents for any occasion</p>
         </div>
         <div class="bg-white rounded-2xl p-8 border border-gray-200">
            <div class="text-4xl mb-4">❤️</div>
            <h3 class="font-serif text-xl mb-2">Help Shelters</h3>
            <p class="text-sm text-gray-600">Every purchase helps pets waiting for their forever homes</p>
         </div>
      </div>
    </div>
  </section>

  <!-- Final CTA Section -->
  <section class="bg-gradient-to-br from-orange-500 to-pink-500 py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-white">Your Pet Deserves <br /> Their Own Anthem</h2>
        
        <div class="flex flex-col md:flex-row justify-center gap-6 mb-10 text-sm font-medium text-white/90">
            <div class="flex items-center gap-2">
                <div class="bg-white text-orange-500 rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Radio-quality songs in minutes
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-white text-orange-500 rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                20% goes to shelter pets
            </div>
        </div>

        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Create Your Song Now &rarr;</Button>
        </div>
    </div>

    <!-- Bottom Illustration -->
    <div class="absolute bottom-0 left-0 right-0 h-32 opacity-20 pointer-events-none flex items-end justify-center overflow-hidden">
        <div class="flex gap-8 text-6xl">
            <span>🐕</span>
            <span>🎵</span>
            <span>🐈</span>
            <span>🎶</span>
            <span>🐇</span>
        </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif mb-16">Frequently Asked Questions</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6">
        {#each [
            "How does Pet Anthemz work?",
            "What types of pets can I create songs for?",
            "How long does it take to create a song?",
            "What genres are available?",
            "Can I preview the song before buying?",
            "How much does it cost?",
            "Can I gift a song to someone else?",
            "Where does the 20% donation go?"
        ] as question}
            <div class="border-b border-gray-200 py-4 flex justify-between items-center group cursor-pointer">
                <span class="font-medium text-lg group-hover:text-orange-brand transition-colors">{question}</span>
                <div class="w-6 h-6 rounded-full bg-dark text-white flex items-center justify-center text-sm group-hover:bg-orange-brand transition-colors">+</div>
            </div>
        {/each}
      </div>
    </div>
  </section>

  <Footer />
</div>

<style>
  /* Custom Scroll Animation */
  @keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  .animate-scroll {
    animation: scroll 20s linear infinite;
  }
  
  @keyframes spin-slow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .animate-spin-slow {
    animation: spin-slow 20s linear infinite;
  }
</style>


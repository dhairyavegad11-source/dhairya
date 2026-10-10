<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LUMEN & VOGUE | Modern Apparel, Accessories & Fragrances</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f9f6f0',
                            100: '#f0eae1',
                            800: '#2c2621',
                            900: '#1a1613',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom smooth scroll and hiding scrollbar for cleaner look */
        html {
            scroll-behavior: smooth;
        }
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }
    </style>
</head>
<body class="bg-stone-50 text-stone-900 font-sans antialiased min-h-screen flex flex-col">

    <!-- Navigation Header -->
    <header class="sticky top-0 z-40 bg-white/90 backdrop-blur-md border-b border-stone-200 transition-all">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand Logo -->
            <div class="flex items-center space-x-3">
                <a href="#" onclick="showSection('shop')" class="text-2xl font-bold tracking-widest text-stone-900 uppercase">
                    LUMEN <span class="font-light text-stone-500">&</span> VOGUE
                </a>
            </div>

            <!-- Desktop Navigation Links -->
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium tracking-wide">
                <a href="#" onclick="filterCategory('All')" class="hover:text-stone-500 transition">ALL PRODUCTS</a>
                <a href="#" onclick="filterCategory('Clothing')" class="hover:text-stone-500 transition">CLOTHING</a>
                <a href="#" onclick="filterCategory('Accessories')" class="hover:text-stone-500 transition">ACCESSORIES</a>
                <a href="#" onclick="filterCategory('Perfumes')" class="hover:text-stone-500 transition">PERFUMES</a>
            </nav>

            <!-- Actions (Search Toggle & Cart Drawer Trigger) -->
            <div class="flex items-center space-x-5">
                <div class="relative hidden sm:block">
                    <input type="text" id="desktopSearch" placeholder="Search products..." 
                           oninput="handleSearch(this.value)"
                           class="pl-9 pr-4 py-2 bg-stone-100 rounded-full text-sm focus:outline-none focus:ring-2 focus:ring-stone-800 w-48 lg:w-64 transition">
                    <i class="fa-solid fa-search absolute left-3.5 top-3 text-stone-400 text-xs"></i>
                </div>

                <button onclick="toggleCart()" class="relative p-2 rounded-full hover:bg-stone-100 transition focus:outline-none" aria-label="Shopping Cart">
                    <i class="fa-solid fa-bag-shopping text-xl"></i>
                    <span id="cartBadge" class="absolute top-0 right-0 bg-stone-900 text-white text-[10px] font-bold w-5 h-5 rounded-full flex items-center justify-center shadow-md hidden">0</span>
                </button>

                <!-- Mobile Menu Button -->
                <button onclick="toggleMobileMenu()" class="md:hidden p-2 rounded-lg hover:bg-stone-100 transition">
                    <i class="fa-solid fa-bars text-xl"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Navigation Drawer -->
        <div id="mobileMenu" class="hidden md:hidden bg-white border-b border-stone-200 px-4 pt-2 pb-4 space-y-3">
            <input type="text" id="mobileSearch" placeholder="Search products..." 
                   oninput="handleSearch(this.value)"
                   class="w-full px-4 py-2 bg-stone-100 rounded-lg text-sm focus:outline-none mb-3">
            <a href="#" onclick="filterCategory('All'); toggleMobileMenu();" class="block py-2 font-medium">All Products</a>
            <a href="#" onclick="filterCategory('Clothing'); toggleMobileMenu();" class="block py-2 font-medium">Clothing</a>
            <a href="#" onclick="filterCategory('Accessories'); toggleMobileMenu();" class="block py-2 font-medium">Accessories</a>
            <a href="#" onclick="filterCategory('Perfumes'); toggleMobileMenu();" class="block py-2 font-medium">Perfumes</a>
        </div>
    </header>

    <!-- Main Content Area -->
    <main class="flex-grow">

        <!-- SECTION 1: SHOP CATALOGUE -->
        <section id="shopSection" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10">
            <!-- Hero Banner -->
            <div class="relative rounded-2xl overflow-hidden bg-stone-900 text-white mb-12 shadow-xl">
                <div class="absolute inset-0 opacity-40 mix-blend-overlay">
                    <img src="https://placehold.co/1400x500/2c2621/ffffff?text=Modern+Collection" alt="Hero Banner" class="w-full h-full object-cover">
                </div>
                <div class="relative px-8 py-20 sm:py-28 md:px-16 max-w-2xl">
                    <span class="text-xs uppercase tracking-widest bg-white/20 px-3 py-1 rounded-full font-semibold">New Season 2026</span>
                    <h1 class="text-4xl sm:text-5xl font-bold tracking-tight mt-4 mb-6">Elevate Your Everyday Style</h1>
                    <p class="text-stone-300 text-base sm:text-lg mb-8 leading-relaxed">Discover our curated selection of premium apparel, handcrafted accessories, and signature fragrances.</p>
                    <a href="#productCatalog" class="inline-block bg-white text-stone-900 font-semibold px-8 py-3.5 rounded-full hover:bg-stone-100 transition shadow-lg">Explore Collection</a>
                </div>
            </div>

            <!-- Filters & Category Navigation Bar -->
            <div id="productCatalog" class="flex flex-col md:flex-row md:items-center justify-between mb-8 gap-4 border-b border-stone-200 pb-6">
                <!-- Categories -->
                <div class="flex items-center space-x-2 sm:space-x-4 overflow-x-auto no-scrollbar pb-2 md:pb-0" id="categoryButtons">
                    <button onclick="filterCategory('All')" class="cat-btn px-5 py-2 rounded-full text-sm font-medium bg-stone-900 text-white transition whitespace-nowrap shadow-sm">All</button>
                    <button onclick="filterCategory('Clothing')" class="cat-btn px-5 py-2 rounded-full text-sm font-medium bg-stone-200 text-stone-700 hover:bg-stone-300 transition whitespace-nowrap">Clothing</button>
                    <button onclick="filterCategory('Accessories')" class="cat-btn px-5 py-2 rounded-full text-sm font-medium bg-stone-200 text-stone-700 hover:bg-stone-300 transition whitespace-nowrap">Accessories</button>
                    <button onclick="filterCategory('Perfumes')" class="cat-btn px-5 py-2 rounded-full text-sm font-medium bg-stone-200 text-stone-700 hover:bg-stone-300 transition whitespace-nowrap">Perfumes</button>
                </div>

                <!-- Sort Filter -->
                <div class="flex items-center space-x-3 self-end md:self-auto">
                    <span class="text-xs font-semibold uppercase text-stone-500 tracking-wider">Sort by:</span>
                    <select id="sortSelect" onchange="sortProducts(this.value)" class="bg-white border border-stone-300 rounded-lg px-3 py-2 text-sm focus:outline-none focus:ring-1 focus:ring-stone-800">
                        <option value="featured">Featured</option>
                        <option value="low-high">Price: Low to High</option>
                        <option value="high-low">Price: High to Low</option>
                    </select>
                </div>
            </div>

            <!-- Product Grid -->
            <div id="productGrid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Dynamic Products will be rendered here -->
            </div>

            <!-- Empty State for Search/Filter -->
            <div id="noResults" class="hidden text-center py-20">
                <i class="fa-solid fa-box-open text-4xl text-stone-300 mb-4"></i>
                <h3 class="text-lg font-semibold text-stone-700">No products found</h3>
                <p class="text-stone-500 text-sm mt-1">Try adjusting your search or category filters.</p>
                <button onclick="filterCategory('All'); document.getElementById('desktopSearch').value='';" class="mt-4 px-6 py-2 bg-stone-900 text-white rounded-full text-sm font-medium">Reset Filters</button>
            </div>
        </section>

        <!-- SECTION 2: PRODUCT DETAILS MODAL / VIEW -->
        <div id="productDetailModal" class="fixed inset-0 z-50 bg-black/60 backdrop-blur-sm hidden flex items-center justify-center p-4">
            <div class="bg-white rounded-2xl max-w-4xl w-full overflow-hidden shadow-2xl relative max-h-[90vh] flex flex-col md:flex-row animate-in fade-in zoom-in duration-200">
                <button onclick="closeProductModal()" class="absolute top-4 right-4 z-10 w-10 h-10 rounded-full bg-stone-100 hover:bg-stone-200 text-stone-700 flex items-center justify-center transition">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
                <!-- Product Image -->
                <div class="md:w-1/2 bg-stone-100 relative min-h-[300px] md:min-h-[500px]">
                    <img id="modalImg" src="" alt="Product" class="w-full h-full object-cover">
                </div>
                <!-- Product Info -->
                <div class="md:w-1/2 p-6 sm:p-10 flex flex-col justify-between overflow-y-auto">
                    <div>
                        <span id="modalCategory" class="text-xs uppercase tracking-widest text-stone-500 font-semibold bg-stone-100 px-2.5 py-1 rounded-md">Category</span>
                        <h2 id="modalTitle" class="text-2xl sm:text-3xl font-bold text-stone-900 mt-3 mb-2">Product Name</h2>
                        <div class="text-xl font-bold text-stone-900 mb-4" id="modalPrice">$0.00</div>
                        <p id="modalDescription" class="text-stone-600 text-sm sm:text-base leading-relaxed mb-6">Detailed product description goes here...</p>

                        <!-- Size / Options if applicable -->
                        <div id="modalSizeContainer" class="mb-6">
                            <label class="block text-xs font-semibold uppercase tracking-wider text-stone-500 mb-2">Select Size</label>
                            <div class="flex space-x-3" id="modalSizes">
                                <button class="size-btn px-4 py-2 border border-stone-300 rounded-lg text-sm font-medium hover:border-stone-900 transition focus:border-stone-900 focus:ring-1 focus:ring-stone-900">S</button>
                                <button class="size-btn px-4 py-2 border border-stone-300 rounded-lg text-sm font-medium hover:border-stone-900 transition focus:border-stone-900 focus:ring-1 focus:ring-stone-900">M</button>
                                <button class="size-btn px-4 py-2 border border-stone-300 rounded-lg text-sm font-medium hover:border-stone-900 transition focus:border-stone-900 focus:ring-1 focus:ring-stone-900">L</button>
                                <button class="size-btn px-4 py-2 border border-stone-300 rounded-lg text-sm font-medium hover:border-stone-900 transition focus:border-stone-900 focus:ring-1 focus:ring-stone-900">XL</button>
                            </div>
                        </div>
                    </div>

                    <div class="space-y-4 pt-6 border-t border-stone-100">
                        <div class="flex items-center space-x-4">
                            <div class="flex items-center border border-stone-300 rounded-lg overflow-hidden">
                                <button onclick="adjustModalQty(-1)" class="px-3 py-2 bg-stone-50 hover:bg-stone-200 transition text-stone-700">-</button>
                                <span id="modalQty" class="px-4 py-2 text-sm font-bold text-stone-900">1</span>
                                <button onclick="adjustModalQty(1)" class="px-3 py-2 bg-stone-50 hover:bg-stone-200 transition text-stone-700">+</button>
                            </div>
                            <button id="modalAddBtn" onclick="addModalToCart()" class="flex-grow bg-stone-900 hover:bg-stone-800 text-white font-semibold py-3 px-6 rounded-lg transition shadow-lg flex items-center justify-center space-x-2">
                                <i class="fa-solid fa-bag-shopping"></i>
                                <span>Add to Cart</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- SECTION 3: CHECKOUT PAGE VIEW -->
        <section id="checkoutSection" class="max-w-4xl mx-auto px-4 py-12 hidden">
            <button onclick="showSection('shop')" class="inline-flex items-center space-x-2 text-stone-600 hover:text-stone-900 mb-8 font-medium text-sm transition">
                <i class="fa-solid fa-arrow-left"></i>
                <span>Back to Shopping</span>
            </button>
            <h1 class="text-3xl font-bold text-stone-900 mb-8">Secure Checkout</h1>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Customer Details Form -->
                <div class="md:col-span-2 bg-white p-6 sm:p-8 rounded-2xl shadow-sm border border-stone-200">
                    <h2 class="text-lg font-bold text-stone-900 mb-6 flex items-center space-x-2">
                        <span class="w-7 h-7 rounded-full bg-stone-900 text-white text-xs flex items-center justify-center">1</span>
                        <span>Shipping Information</span>
                    </h2>
                    <form id="checkoutForm" onsubmit="handleCheckoutSubmit(event)" class="space-y-4">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">First Name</label>
                                <input type="text" required class="w-full px-4 py-2.5 rounded-lg border border-stone-300 text-sm focus:outline-none focus:ring-2 focus:ring-stone-800" placeholder="Alex">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">Last Name</label>
                                <input type="text" required class="w-full px-4 py-2.5 rounded-lg border border-stone-300 text-sm focus:outline-none focus:ring-2 focus:ring-stone-800" placeholder="Morgan">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">Email Address</label>
                            <input type="email" required class="w-full px-4 py-2.5 rounded-lg border border-stone-300 text-sm focus:outline-none focus:ring-2 focus:ring-stone-800" placeholder="alex.morgan@example.com">
                        </div>
                        <div>
                            <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">Street Address</label>
                            <input type="text" required class="w-full px-4 py-2.5 rounded-lg border border-stone-300 text-sm focus:outline-none focus:ring-2 focus:ring-stone-800" placeholder="123 Fashion Ave, Suite 4B">
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                            <div>
                                <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">City</label>
                                <input type="text" required class="w-full px-4 py-2.5 rounded-lg border border-stone-300 text-sm focus:outline-none focus:ring-2 focus:ring-stone-800" placeholder="New York">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">State / Prov</label>
                                <input type="text" required class="w-full px-4 py-2.5 rounded-lg border border-stone-300 text-sm focus:outline-none focus:ring-2 focus:ring-stone-800" placeholder="NY">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">Postal Code</label>
                                <input type="text" required class="w-full px-4 py-2.5 rounded-lg border border-stone-300 text-sm focus:outline-none focus:ring-2 focus:ring-stone-800" placeholder="10001">
                            </div>
                        </div>

                        <h2 class="text-lg font-bold text-stone-900 mt-8 mb-6 flex items-center space-x-2">
                            <span class="w-7 h-7 rounded-full bg-stone-900 text-white text-xs flex items-center justify-center">2</span>
                            <span>Payment Options</span>
                        </h2>

                        <div class="space-y-3">
                            <label class="flex items-center space-x-3 p-3.5 rounded-lg border border-stone-300 cursor-pointer hover:bg-stone-50 transition">
                                <input type="radio" name="payment" value="UPI" checked onclick="togglePaymentDetails('UPI')" class="text-stone-900 focus:ring-stone-900">
                                <div class="flex items-center space-x-3">
                                    <i class="fa-solid fa-mobile-screen-button text-lg text-stone-700"></i>
                                    <div>
                                        <p class="text-sm font-semibold text-stone-900">UPI / QR Code</p>
                                        <p class="text-xs text-stone-500">GPay, PhonePe, Paytm, or BHIM</p>
                                    </div>
                                </div>
                            </label>

                            <label class="flex items-center space-x-3 p-3.5 rounded-lg border border-stone-300 cursor-pointer hover:bg-stone-50 transition">
                                <input type="radio" name="payment" value="Card" onclick="togglePaymentDetails('Card')" class="text-stone-900 focus:ring-stone-900">
                                <div class="flex items-center space-x-3">
                                    <i class="fa-regular fa-credit-card text-lg text-stone-700"></i>
                                    <div>
                                        <p class="text-sm font-semibold text-stone-900">Credit / Debit Card</p>
                                        <p class="text-xs text-stone-500">Visa, Mastercard, RuPay, Amex</p>
                                    </div>
                                </div>
                            </label>

                            <label class="flex items-center space-x-3 p-3.5 rounded-lg border border-stone-300 cursor-pointer hover:bg-stone-50 transition">
                                <input type="radio" name="payment" value="COD" onclick="togglePaymentDetails('COD')" class="text-stone-900 focus:ring-stone-900">
                                <div class="flex items-center space-x-3">
                                    <i class="fa-solid fa-money-bill-wave text-lg text-stone-700"></i>
                                    <div>
                                        <p class="text-sm font-semibold text-stone-900">Cash on Delivery (COD)</p>
                                        <p class="text-xs text-stone-500">Pay when your order arrives</p>
                                    </div>
                                </div>
                            </label>
                        </div>

                        <!-- Dynamic Payment Inputs -->
                        <div id="upiFields" class="mt-4 p-4 bg-stone-50 rounded-lg border border-stone-200">
                            <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">UPI ID / VPA</label>
                            <input type="text" class="w-full px-4 py-2 rounded-lg border border-stone-300 text-sm bg-white" placeholder="username@oksbi">
                        </div>

                        <div id="cardFields" class="mt-4 p-4 bg-stone-50 rounded-lg border border-stone-200 hidden space-y-3">
                            <div>
                                <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">Card Number</label>
                                <input type="text" class="w-full px-4 py-2 rounded-lg border border-stone-300 text-sm bg-white" placeholder="4532 •••• •••• 8920">
                            </div>
                            <div class="grid grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">Expiry Date</label>
                                    <input type="text" class="w-full px-4 py-2 rounded-lg border border-stone-300 text-sm bg-white" placeholder="MM/YY">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold uppercase text-stone-600 mb-1">CVV</label>
                                    <input type="password" maxlength="4" class="w-full px-4 py-2 rounded-lg border border-stone-300 text-sm bg-white" placeholder="123">
                                </div>
                            </div>
                        </div>

                        <button type="submit" class="w-full mt-8 bg-stone-900 hover:bg-stone-800 text-white font-semibold py-4 rounded-xl transition shadow-xl text-base">
                            Place Order (<span id="checkoutTotalBtn">$0.00</span>)
                        </button>
                    </form>
                </div>

                <!-- Order Summary Side Card -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-stone-200 h-fit">
                    <h3 class="text-base font-bold text-stone-900 mb-4 pb-3 border-b border-stone-200">Order Summary</h3>
                    <div id="checkoutSummaryItems" class="space-y-3 max-h-60 overflow-y-auto pr-1 mb-4">
                        <!-- Items rendered dynamically -->
                    </div>
                    <div class="space-y-2 pt-4 border-t border-stone-200 text-sm">
                        <div class="flex justify-between text-stone-600">
                            <span>Subtotal</span>
                            <span id="checkoutSubtotal">$0.00</span>
                        </div>
                        <div class="flex justify-between text-stone-600">
                            <span>Shipping</span>
                            <span class="text-emerald-600 font-medium">Free</span>
                        </div>
                        <div class="flex justify-between text-stone-900 font-bold text-base pt-2 border-t border-stone-100">
                            <span>Total</span>
                            <span id="checkoutTotal">$0.00</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- SECTION 4: ORDER CONFIRMATION VIEW -->
        <section id="confirmationSection" class="max-w-2xl mx-auto px-4 py-20 text-center hidden">
            <div class="w-20 h-20 bg-emerald-100 text-emerald-600 rounded-full flex items-center justify-center mx-auto mb-6 text-3xl shadow-inner">
                <i class="fa-solid fa-check"></i>
            </div>
            <span class="text-xs uppercase tracking-widest text-stone-500 font-semibold bg-stone-100 px-3 py-1 rounded-full">Success</span>
            <h1 class="text-3xl sm:text-4xl font-bold text-stone-900 mt-4 mb-2">Order Confirmed!</h1>
            <p class="text-stone-600 text-base mb-8">Thank you for your purchase. We've received your order and are getting it ready for shipment.</p>
            
            <div class="bg-white p-6 rounded-2xl border border-stone-200 shadow-sm text-left mb-8 space-y-3">
                <div class="flex justify-between text-sm pb-3 border-b border-stone-100">
                    <span class="text-stone-500">Order Number:</span>
                    <span id="confOrderNo" class="font-bold text-stone-900">#LV-84920</span>
                </div>
                <div class="flex justify-between text-sm pb-3 border-b border-stone-100">
                    <span class="text-stone-500">Payment Mode:</span>
                    <span id="confPaymentMode" class="font-bold text-stone-900">UPI</span>
                </div>
                <div class="flex justify-between text-sm pb-3 border-b border-stone-100">
                    <span class="text-stone-500">Estimated Delivery:</span>
                    <span class="font-bold text-stone-900">3-5 Business Days</span>
                </div>
                <div class="flex justify-between text-sm">
                    <span class="text-stone-500">Total Amount Paid:</span>
                    <span id="confTotal" class="font-bold text-stone-900">$0.00</span>
                </div>
            </div>

            <button onclick="resetStoreAndHome()" class="bg-stone-900 hover:bg-stone-800 text-white font-semibold px-8 py-3.5 rounded-full transition shadow-lg text-sm">
                Continue Shopping
            </button>
        </section>

    </main>

    <!-- Slide-over Shopping Cart Drawer -->
    <div id="cartOverlay" class="fixed inset-0 z-50 bg-black/50 backdrop-blur-sm hidden transition-opacity" onclick="toggleCart()"></div>
    <div id="cartDrawer" class="fixed top-0 right-0 z-50 h-full w-full max-w-md bg-white shadow-2xl transform translate-x-full transition-transform duration-300 ease-in-out flex flex-col">
        <!-- Cart Header -->
        <div class="px-6 py-5 border-b border-stone-200 flex items-center justify-between">
            <h2 class="text-lg font-bold text-stone-900 flex items-center space-x-2">
                <i class="fa-solid fa-bag-shopping"></i>
                <span>Your Cart (<span id="cartCountTitle">0</span>)</span>
            </h2>
            <button onclick="toggleCart()" class="p-2 text-stone-500 hover:text-stone-900 rounded-lg transition">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
        </div>

        <!-- Cart Items List -->
        <div id="cartItemsList" class="flex-grow overflow-y-auto p-6 space-y-4 divide-y divide-stone-100">
            <!-- Rendered dynamically -->
        </div>

        <!-- Cart Footer -->
        <div class="p-6 border-t border-stone-200 bg-stone-50 space-y-4">
            <div class="space-y-1.5 text-sm">
                <div class="flex justify-between text-stone-600">
                    <span>Subtotal</span>
                    <span id="cartSubtotal" class="font-semibold text-stone-900">$0.00</span>
                </div>
                <div class="flex justify-between text-stone-600">
                    <span>Shipping</span>
                    <span class="text-emerald-600 font-medium">Calculated at checkout</span>
                </div>
                <div class="flex justify-between text-base font-bold text-stone-900 pt-2 border-t border-stone-200">
                    <span>Total</span>
                    <span id="cartTotal">$0.00</span>
                </div>
            </div>
            <button onclick="proceedToCheckout()" id="checkoutBtn" class="w-full bg-stone-900 hover:bg-stone-800 text-white font-semibold py-3.5 rounded-xl transition shadow-lg flex items-center justify-center space-x-2 disabled:opacity-50 disabled:cursor-not-allowed">
                <span>Proceed to Checkout</span>
                <i class="fa-solid fa-arrow-right text-xs"></i>
            </button>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-stone-900 text-stone-400 py-12 border-t border-stone-800 mt-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
            <div>
                <h3 class="text-white text-lg font-bold tracking-widest uppercase mb-4">LUMEN & VOGUE</h3>
                <p class="text-sm leading-relaxed">Elevating personal style with timeless apparel, refined accessories, and signature luxury fragrances.</p>
            </div>
            <div>
                <h4 class="text-white text-sm font-semibold uppercase tracking-wider mb-4">Quick Links</h4>
                <ul class="space-y-2 text-sm">
                    <li><a href="#" onclick="filterCategory('All')" class="hover:text-white transition">All Products</a></li>
                    <li><a href="#" onclick="filterCategory('Clothing')" class="hover:text-white transition">Clothing</a></li>
                    <li><a href="#" onclick="filterCategory('Accessories')" class="hover:text-white transition">Accessories</a></li>
                    <li><a href="#" onclick="filterCategory('Perfumes')" class="hover:text-white transition">Perfumes</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white text-sm font-semibold uppercase tracking-wider mb-4">Customer Support</h4>
                <ul class="space-y-2 text-sm">
                    <li><a href="#" class="hover:text-white transition">Shipping & Returns</a></li>
                    <li><a href="#" class="hover:text-white transition">Track Your Order</a></li>
                    <li><a href="#" class="hover:text-white transition">Size Guide</a></li>
                    <li><a href="#" class="hover:text-white transition">Contact Us</a></li>
                </ul>
            </div>
            <div>
                <h4 class="text-white text-sm font-semibold uppercase tracking-wider mb-4">Newsletter</h4>
                <p class="text-sm mb-4">Subscribe to receive updates, access to exclusive deals, and more.</p>
                <div class="flex">
                    <input type="email" placeholder="Your email address" class="bg-stone-800 text-white px-4 py-2 text-sm rounded-l-lg focus:outline-none w-full">
                    <button class="bg-white text-stone-900 px-4 py-2 text-sm font-semibold rounded-r-lg hover:bg-stone-200 transition">Join</button>
                </div>
            </div>
        </div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-8 border-t border-stone-800 text-center text-xs text-stone-500">
            &copy; 2026 LUMEN & VOGUE. All rights reserved. Designed with modern aesthetics.
        </div>
    </footer>

    <!-- JavaScript Application Logic -->
    <script>
        // Product Database
        const products = [
            {
                id: 1,
                name: "Oversized Cashmere Blend Hoodie",
                category: "Clothing",
                price: 128.00,
                rating: 4.8,
                image: "https://placehold.co/600x800/e6e2dd/2c2621?text=Cashmere+Hoodie",
                description: "Luxuriously soft cashmere blend hoodie designed for ultimate comfort and effortless street style. Features ribbed cuffs and a relaxed drop-shoulder fit.",
                sizes: ["S", "M", "L", "XL"],
                featured: true
            },
            {
                id: 2,
                name: "Tailored Wool Trench Coat",
                category: "Clothing",
                price: 245.00,
                rating: 4.9,
                image: "https://placehold.co/600x800/dcd4cb/2c2621?text=Wool+Trench+Coat",
                description: "Impeccably tailored double-breasted trench coat crafted from premium virgin wool. A timeless staple for cooler seasons.",
                sizes: ["S", "M", "L"],
                featured: true
            },
            {
                id: 3,
                name: "Minimalist Leather Crossbody Bag",
                category: "Accessories",
                price: 185.00,
                rating: 4.7,
                image: "https://placehold.co/600x800/d4cdc4/2c2621?text=Leather+Crossbody",
                description: "Crafted from full-grain supple leather with custom brushed hardware. Compact yet spacious enough for your daily essentials.",
                sizes: ["One Size"],
                featured: true
            },
            {
                id: 4,
                name: "Nocturne Eau de Parfum (100ml)",
                category: "Perfumes",
                price: 140.00,
                rating: 4.9,
                image: "https://placehold.co/600x800/c9c0b5/2c2621?text=Nocturne+Perfume",
                description: "An intoxicating blend of warm amber, Madagascar vanilla, and dark orchid wood notes. Sophisticated and long-lasting.",
                sizes: ["50ml", "100ml"],
                featured: true
            },
            {
                id: 5,
                name: "Pleated Midi Wrap Skirt",
                category: "Clothing",
                price: 95.00,
                rating: 4.6,
                image: "https://placehold.co/600x800/e3ddd5/2c2621?text=Pleated+Midi+Skirt",
                description: "Flowing pleated midi skirt with an adjustable wrap tie waist. Moves gracefully with every step.",
                sizes: ["S", "M", "L"],
                featured: false
            },
            {
                id: 6,
                name: "Titanium Matte Aviator Sunglasses",
                category: "Accessories",
                price: 115.00,
                rating: 4.5,
                image: "https://placehold.co/600x800/ded6cc/2c2621?text=Aviator+Sunglasses",
                description: "Lightweight titanium frames with polarized UV400 gradient lenses. Combines vintage aesthetics with modern durability.",
                sizes: ["Standard"],
                featured: false
            },
            {
                id: 7,
                name: "Santal Nomade Extrait de Parfum",
                category: "Perfumes",
                price: 165.00,
                rating: 5.0,
                image: "https://placehold.co/600x800/cfc6bc/2c2621?text=Santal+Nomade",
                description: "Rich Australian sandalwood infused with cardamom, violet leaf, and leather accords. Warm, woody, and captivating.",
                sizes: ["100ml"],
                featured: true
            },
            {
                id: 8,
                name: "Ribbed Merino Wool Beanie",
                category: "Accessories",
                price: 55.00,
                rating: 4.4,
                image: "https://placehold.co/600x800/d9d0c7/2c2621?text=Merino+Beanie",
                description: "Ultra-fine merino wool beanie that provides exceptional warmth without the itch. Perfect winter accessory.",
                sizes: ["One Size"],
                featured: false
            }
        ];

        // Application State
        let cart = [];
        let currentCategory = 'All';
        let searchQuery = '';
        let currentSort = 'featured';
        let selectedProduct = null;
        let selectedModalSize = null;
        let modalQtyValue = 1;

        // Initialize application on load
        window.onload = function() {
            renderProducts();
            updateCartUI();
        };

        // Render Product Catalog
        function renderProducts() {
            const grid = document.getElementById('productGrid');
            const noResults = document.getElementById('noResults');
            
            // Filter products
            let filtered = products.filter(p => {
                const matchesCat = currentCategory === 'All' || p.category === currentCategory;
                const matchesSearch = p.name.toLowerCase().includes(searchQuery.toLowerCase()) || 
                                      p.description.toLowerCase().includes(searchQuery.toLowerCase()) ||
                                      p.category.toLowerCase().includes(searchQuery.toLowerCase());
                return matchesCat && matchesSearch;
            });

            // Sort products
            if (currentSort === 'low-high') {
                filtered.sort((a, b) => a.price - b.price);
            } else if (currentSort === 'high-low') {
                filtered.sort((a, b) => b.price - a.price);
            }

            if (filtered.length === 0) {
                grid.innerHTML = '';
                noResults.classList.remove('hidden');
                return;
            }

            noResults.classList.add('hidden');
            grid.innerHTML = filtered.map(p => `
                <div class="group bg-white rounded-2xl overflow-hidden border border-stone-200 shadow-sm hover:shadow-xl transition flex flex-col justify-between">
                    <div class="relative bg-stone-100 aspect-[3/4] overflow-hidden cursor-pointer" onclick="openProductModal(${p.id})">
                        <img src="${p.image}" alt="${p.name}" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                        <span class="absolute top-3 left-3 bg-white/90 backdrop-blur-sm text-stone-900 text-[10px] font-bold uppercase px-2.5 py-1 rounded-md tracking-wider shadow-sm">${p.category}</span>
                    </div>
                    <div class="p-5 flex flex-col flex-grow justify-between">
                        <div>
                            <div class="flex items-center justify-between text-xs text-stone-500 mb-1">
                                <span><i class="fa-solid fa-star text-amber-400 mr-1"></i>${p.rating}</span>
                            </div>
                            <h3 onclick="openProductModal(${p.id})" class="font-bold text-stone-900 text-base line-clamp-1 hover:text-stone-600 cursor-pointer transition">${p.name}</h3>
                            <p class="text-stone-500 text-xs line-clamp-2 mt-1">${p.description}</p>
                        </div>
                        <div class="mt-4 pt-4 border-t border-stone-100 flex items-center justify-between">
                            <span class="text-lg font-bold text-stone-900">$${p.price.toFixed(2)}</span>
                            <button onclick="quickAddToCart(${p.id})" class="bg-stone-900 hover:bg-stone-800 text-white text-xs font-semibold px-4 py-2.5 rounded-lg transition shadow-md flex items-center space-x-1.5">
                                <i class="fa-solid fa-plus text-[10px]"></i>
                                <span>Add</span>
                            </button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        // Category Filter
        function filterCategory(cat) {
            currentCategory = cat;
            // Update button styles
            document.querySelectorAll('.cat-btn').forEach(btn => {
                if (btn.textContent.trim() === cat || (cat === 'All' && btn.textContent.trim() === 'All')) {
                    btn.className = "cat-btn px-5 py-2 rounded-full text-sm font-medium bg-stone-900 text-white transition whitespace-nowrap shadow-sm";
                } else {
                    btn.className = "cat-btn px-5 py-2 rounded-full text-sm font-medium bg-stone-200 text-stone-700 hover:bg-stone-300 transition whitespace-nowrap";
                }
            });
            renderProducts();
        }

        // Search Handler
        function handleSearch(query) {
            searchQuery = query;
            // Sync desktop and mobile search inputs
            document.getElementById('desktopSearch').value = query;
            document.getElementById('mobileSearch').value = query;
            renderProducts();
        }

        // Sort Handler
        function sortProducts(val) {
            currentSort = val;
            renderProducts();
        }

        // Product Modal Operations
        function openProductModal(id) {
            selectedProduct = products.find(p => p.id === id);
            if (!selectedProduct) return;

            modalQtyValue = 1;
            selectedModalSize = selectedProduct.sizes[0] || 'Standard';

            document.getElementById('modalImg').src = selectedProduct.image;
            document.getElementById('modalCategory').textContent = selectedProduct.category;
            document.getElementById('modalTitle').textContent = selectedProduct.name;
            document.getElementById('modalPrice').textContent = `$${selectedProduct.price.toFixed(2)}`;
            document.getElementById('modalDescription').textContent = selectedProduct.description;
            document.getElementById('modalQty').textContent = modalQtyValue;

            // Render sizes
            const sizeContainer = document.getElementById('modalSizes');
            sizeContainer.innerHTML = selectedProduct.sizes.map((s, idx) => `
                <button onclick="selectModalSize('${s}')" class="size-btn px-4 py-2 border rounded-lg text-sm font-medium transition ${idx === 0 ? 'border-stone-900 bg-stone-900 text-white' : 'border-stone-300 text-stone-700 hover:border-stone-900'}">${s}</button>
            `).join('');

            document.getElementById('productDetailModal').classList.remove('hidden');
        }

        function closeProductModal() {
            document.getElementById('productDetailModal').classList.add('hidden');
            selectedProduct = null;
        }

        function selectModalSize(size) {
            selectedModalSize = size;
            document.querySelectorAll('.size-btn').forEach(btn => {
                if (btn.textContent.trim() === size) {
                    btn.className = "size-btn px-4 py-2 border rounded-lg text-sm font-medium transition border-stone-900 bg-stone-900 text-white";
                } else {
                    btn.className = "size-btn px-4 py-2 border rounded-lg text-sm font-medium transition border-stone-300 text-stone-700 hover:border-stone-900";
                }
            });
        }

        function adjustModalQty(change) {
            modalQtyValue = Math.max(1, modalQtyValue + change);
            document.getElementById('modalQty').textContent = modalQtyValue;
        }

        function addModalToCart() {
            if (!selectedProduct) return;
            addToCart(selectedProduct.id, modalQtyValue, selectedModalSize);
            closeProductModal();
            toggleCart();
        }

        function quickAddToCart(id) {
            const prod = products.find(p => p.id === id);
            if (!prod) return;
            addToCart(id, 1, prod.sizes[0] || 'Standard');
            toggleCart();
        }

        // Cart Management Logic
        function addToCart(productId, quantity, size) {
            const product = products.find(p => p.id === productId);
            if (!product) return;

            const existingIndex = cart.findIndex(item => item.id === productId && item.size === size);
            if (existingIndex > -1) {
                cart[existingIndex].quantity += quantity;
            } else {
                cart.push({
                    id: product.id,
                    name: product.name,
                    price: product.price,
                    image: product.image,
                    category: product.category,
                    size: size,
                    quantity: quantity
                });
            }
            updateCartUI();
        }

        function updateQuantity(index, change) {
            cart[index].quantity += change;
            if (cart[index].quantity <= 0) {
                cart.splice(index, 1);
            }
            updateCartUI();
        }

        function removeFromCart(index) {
            cart.splice(index, 1);
            updateCartUI();
        }

        function updateCartUI() {
            const badge = document.getElementById('cartBadge');
            const cartCountTitle = document.getElementById('cartCountTitle');
            const cartItemsList = document.getElementById('cartItemsList');
            const cartSubtotal = document.getElementById('cartSubtotal');
            const cartTotal = document.getElementById('cartTotal');
            const checkoutBtn = document.getElementById('checkoutBtn');

            const totalCount = cart.reduce((sum, item) => sum + item.quantity, 0);
            const subtotal = cart.reduce((sum, item) => sum + (item.price * item.quantity), 0);

            // Badge updates
            if (totalCount > 0) {
                badge.textContent = totalCount;
                badge.classList.remove('hidden');
                checkoutBtn.disabled = false;
            } else {
                badge.classList.add('hidden');
                checkoutBtn.disabled = true;
            }

            cartCountTitle.textContent = totalCount;
            cartSubtotal.textContent = `$${subtotal.toFixed(2)}`;
            cartTotal.textContent = `$${subtotal.toFixed(2)}`;

            // Render Cart Items
            if (cart.length === 0) {
                cartItemsList.innerHTML = `
                    <div class="text-center py-20">
                        <i class="fa-solid fa-bag-shopping text-4xl text-stone-300 mb-3"></i>
                        <p class="text-stone-500 text-sm">Your cart is currently empty.</p>
                    </div>
                `;
                return;
            }

            cartItemsList.innerHTML = cart.map((item, idx) => `
                <div class="flex items-center space-x-4 py-4 first:pt-0 last:pb-0">
                    <img src="${item.image}" alt="${item.name}" class="w-20 h-20 object-cover rounded-xl bg-stone-100 flex-shrink-0">
                    <div class="flex-grow">
                        <h4 class="text-sm font-bold text-stone-900 line-clamp-1">${item.name}</h4>
                        <p class="text-xs text-stone-500 mt-0.5">Size: <span class="font-medium text-stone-700">${item.size}</span></p>
                        <div class="flex items-center justify-between mt-3">
                            <div class="flex items-center border border-stone-200 rounded-lg overflow-hidden">
                                <button onclick="updateQuantity(${idx}, -1)" class="px-2.5 py-1 bg-stone-50 hover:bg-stone-200 transition text-stone-700 text-xs">-</button>
                                <span class="px-3 py-1 text-xs font-bold text-stone-900">${item.quantity}</span>
                                <button onclick="updateQuantity(${idx}, 1)" class="px-2.5 py-1 bg-stone-50 hover:bg-stone-200 transition text-stone-700 text-xs">+</button>
                            </div>
                            <span class="text-sm font-bold text-stone-900">$${(item.price * item.quantity).toFixed(2)}</span>
                        </div>
                    </div>
                    <button onclick="removeFromCart(${idx})" class="text-stone-400 hover:text-rose-600 transition p-2">
                        <i class="fa-solid fa-trash-can text-sm"></i>
                    </button>
                </div>
            `).join('');
        }

        // Cart Drawer Toggle
        function toggleCart() {
            const drawer = document.getElementById('cartDrawer');
            const overlay = document.getElementById('cartOverlay');
            const isOpen = !drawer.classList.contains('translate-x-full');

            if (isOpen) {
                drawer.classList.add('translate-x-full');
                overlay.classList.add('hidden');
            } else {
                drawer.classList.remove('translate-x-full');
                overlay.classList.remove('hidden');
                updateCartUI();
            }
        }

        // Mobile Menu Toggle
        function toggleMobileMenu() {
            const menu = document.getElementById('mobileMenu');
            menu.classList.toggle('hidden');
        }

        // Navigation between sections (Shop, Checkout, Confirmation)
        function showSection(sectionName) {
            const shopSec = document.getElementById('shopSection');
            const checkoutSec = document.getElementById('checkoutSection');
            const confSec = document.getElementById('confirmationSection');

            shopSec.classList.add('hidden');
            checkoutSec.classList.add('hidden');
            confSec.classList.add('hidden');

            window.scrollTo({ top: 0, behavior: 'smooth' });

            if (sectionName === 'shop') {
                shopSec.classList.remove('hidden');
            } else if (sectionName === 'checkout') {
                checkoutSec.classList.remove('hidden');
                populateCheckoutSummary();
            } else if (sectionName === 'confirmation') {
                confSec.classList.remove('hidden');
            }
        }

        // Proceed to Checkout
        function proceedToCheckout() {
            if (cart.length === 0) return;
            toggleCart(); // Close cart drawer
            showSection('checkout');
        }

        // Payment Option Toggles
        function togglePaymentDetails(mode) {
            const upiFields = document.getElementById('upiFields');
            const cardFields = document.getElementById('cardFields');

            upiFields.classList.add('hidden');
            cardFields.classList.add('hidden');

            if (mode === 'UPI') {
                upiFields.classList.remove('hidden');
            } else if (mode === 'Card') {
                cardFields.classList.remove('hidden');
            }
        }

        // Populate Checkout Summary
        function populateCheckoutSummary() {
            const container = document.getElementById('checkoutSummaryItems');
            const subtotalEl = document.getElementById('checkoutSubtotal');
            const totalEl = document.getElementById('checkoutTotal');
            const totalBtn = document.getElementById('checkoutTotalBtn');

            const subtotal = cart.reduce((sum, item) => sum + (item.price * item.quantity), 0);

            container.innerHTML = cart.map(item => `
                <div class="flex items-center justify-between text-sm">
                    <div class="flex items-center space-x-3 pr-2">
                        <img src="${item.image}" class="w-10 h-10 object-cover rounded-lg bg-stone-100 flex-shrink-0">
                        <div>
                            <p class="font-medium text-stone-900 line-clamp-1">${item.name}</p>
                            <p class="text-xs text-stone-500">Qty: ${item.quantity} | Size: ${item.size}</p>
                        </div>
                    </div>
                    <span class="font-semibold text-stone-900">$${(item.price * item.quantity).toFixed(2)}</span>
                </div>
            `).join('');

            subtotalEl.textContent = `$${subtotal.toFixed(2)}`;
            totalEl.textContent = `$${subtotal.toFixed(2)}`;
            totalBtn.textContent = `$${subtotal.toFixed(2)}`;
        }

        // Checkout Form Submit
        function handleCheckoutSubmit(e) {
            e.preventDefault();
            const subtotal = cart.reduce((sum, item) => sum + (item.price * item.quantity), 0);
            const paymentMode = document.querySelector('input[name="payment"]:checked').value;

            // Set confirmation details
            document.getElementById('confOrderNo').textContent = `#LV-${Math.floor(10000 + Math.random() * 90000)}`;
            document.getElementById('confPaymentMode').textContent = paymentMode === 'COD' ? 'Cash on Delivery' : (paymentMode === 'UPI' ? 'UPI / QR Code' : 'Credit / Debit Card');
            document.getElementById('confTotal').textContent = `$${subtotal.toFixed(2)}`;

            // Clear cart
            cart = [];
            updateCartUI();

            showSection('confirmation');
        }

        // Reset Store and Return Home
        function resetStoreAndHome() {
            showSection('shop');
            filterCategory('All');
        }
    </script>
</body>
</html>

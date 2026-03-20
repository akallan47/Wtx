

export default function Website() {
  return (
    <div className="min-h-screen bg-gray-50 text-gray-900">
      {/* Header */}
      <header className="bg-black text-white p-6 shadow-md">
        <h1 className="text-3xl font-bold">West Texas Trading</h1>
        <p className="text-sm mt-1">Built on Christ • Trading Cards & Collectibles</p>
      </header>

      {/* Hero Section */}
      <section className="text-center py-16 px-6">
        <h2 className="text-4xl font-bold mb-4">Buy. Sell. Collect.</h2>
        <p className="max-w-xl mx-auto text-lg text-gray-600">
          Your trusted source for Pokémon, sports cards, and collectibles. Built on faith, focused on value.
        </p>
        <button className="mt-6 bg-black text-white px-6 py-3 rounded-2xl shadow hover:bg-gray-800">
          Shop Now
        </button>
      </section>

      {/* Products Section */}
      <section className="py-12 px-6">
        <h3 className="text-2xl font-bold mb-6 text-center">What We Offer</h3>
        <div className="grid md:grid-cols-3 gap-6">
          <div className="bg-white p-6 rounded-2xl shadow">
            <h4 className="font-bold text-xl mb-2">Pokémon Cards</h4>
            <p className="text-gray-600">Sealed packs, booster boxes, and singles.</p>
          </div>
          <div className="bg-white p-6 rounded-2xl shadow">
            <h4 className="font-bold text-xl mb-2">Sports Cards</h4>
            <p className="text-gray-600">NFL, NBA, MLB, and more collectibles.</p>
          </div>
          <div className="bg-white p-6 rounded-2xl shadow">
            <h4 className="font-bold text-xl mb-2">Magic & More</h4>
            <p className="text-gray-600">Magic: The Gathering and other TCGs.</p>
          </div>
        </div>
      </section>

      {/* About Section */}
      <section className="bg-white py-12 px-6 text-center">
        <h3 className="text-2xl font-bold mb-4">Our Mission</h3>
        <p className="max-w-2xl mx-auto text-gray-600">
          West Texas Trading is founded on Christ. Our mission is to provide honest pricing, build community, and bring integrity back to the trading card space.
        </p>
      </section>

      {/* Contact Section */}
      <section className="py-12 px-6 text-center">
        <h3 className="text-2xl font-bold mb-4">Contact Us</h3>
        <p className="text-gray-600">Email: westtexastrading@email.com</p>
      </section>

      {/* Footer */}
      <footer className="bg-black text-white text-center p-6 mt-10">
        <p>© {new Date().getFullYear()} West Texas Trading. All rights reserved.</p>
      </footer>
    </div>
  );
}
